# Maintainer: Aleksy Grabowski <hurufu+arch@gmail.com>

pkgname=nexoid-nexui-flask-systemd
pkgver=0.0.1
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
md5sums=('00790eb3fbdc274f33747dba68a9647a')
sha1sums=('4a3e9b4278c03e5608209f5f61ce31bdda555aa0')

package() {
    install -Dm444 -t "$pkgdir/usr/lib/systemd/system" nexui.service
}
