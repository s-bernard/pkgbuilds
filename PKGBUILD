# Maintainer: Sabu Siyad <ssiyad at disroot dot org>

pkgname=shelby-bin
pkgver=1.0.2
pkgrel=1
pkgdesc="A fast, lightweight, minimal, shell prompt written in Go"
arch=('x86_64')
url="https://github.com/athul/shelby"
license=("GNU General Public License v3.0")
source=(
    "shelby_${pkgver}_Linux_x86_64.tar.gz::https://github.com/athul/shelby/releases/download/v${pkgver}/shelby_${pkgver}_Linux_x86_64.tar.gz"
)
sha256sums=('0feed5fa90cb9fb20ca48390402aed78acb68b70664d73a112f77ac396048b89')

package() {
    install -D "${srcdir}/shelby" "${pkgdir}/usr/local/bin/shelby"
    install -D "${srcdir}/LICENSE" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
}
