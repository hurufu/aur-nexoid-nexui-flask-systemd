# Maintainer: Aleksy Grabowski <hurufu+arch@gmail.com>

pkgname=nexoid-nexui-flask-systemd
pkgver=0.0.2
pkgrel=1
pkgdesc='systemd unit file for nexoid-nexui-flask'
arch=(any)
license=('AGPL')
groups=(nexoid)
depends=(
    systemd
    ufw
    nexoid-nexui-flask
)

install=nexui.install

source=(
    nexui.service
)
md5sums=('7d3bb65abb98d8d7746ea9fcd121edc4')
sha1sums=('d9e0c20198d7bc926e66f01df07d02d66235f73c')

package() {
    install -Dm444 -t "$pkgdir/usr/lib/systemd/system" nexui.service
}
