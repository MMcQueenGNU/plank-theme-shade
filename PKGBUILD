# Maintainer: McQueen <clear3239@yahoo.com>

pkgname=plank-theme-shade
pkgver=0.1
pkgrel=1
arch=('any')
url='https://github.com/kennyh7279/plank-themes'
license=('GPL3')
depends=('plank')
makedepends=('git')
source=("git://github.com/MMcQueenGNU/plank-theme-shade.git")
sha256sums=('SKIP')

build() {
	true
}

package() {
	cd $srcdir/$pkgname
	mkdir -p $pkgdir/usr/share/plank/themes/shade
	install -m 755 dock.theme $pkgdir/usr/share/plank/themes/shade/
}
