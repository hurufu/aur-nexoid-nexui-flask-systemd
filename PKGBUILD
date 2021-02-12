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
    nexoid-nexui-flask-git
)

install=nexui.install

source=(
    nexui.service
)
md5sums=(
    179174b2f27bc612fb35375fff9c9933
)
sha1sums=(
    e86244af11cabbb40e2b14185b675040e0674386
)

package() {
    install -Dm444 -t "$pkgdir/usr/lib/systemd/system" nexui.service
}
