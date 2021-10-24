# Maintainer: Aditya Shakya <adi1090x@gmail.com>

pkgname=icon-packs
pkgver=1.0
pkgrel=1
pkgdesc="Arc Icon theme for Archcraft"
arch=('any')
license=('GPL3')
makedepends=()
depends=()
conflicts=()
groups=()
provides=("${pkgname}")
options=(!strip !emptydirs)

prepare() {
	cp -af ../files/. ${srcdir}
}

package() {
	local _iconsdir=${pkgdir}/usr/share/icons
	mkdir -p "$_iconsdir"
	cp -r ${srcdir}/* "$_iconsdir"
}
