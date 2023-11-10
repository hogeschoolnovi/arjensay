# Maintainer: Itekr (Oscar) <odin@mimitzbruner.ofzo>
pkgname=arjensay
pkgver=1.0.0
pkgrel=1
pkgdesc=" Cowsay maar dan met Arjen!"
arch=(any)
url="https://github.com/hogeschoolnovi/arjensay"
license=('GPL')
depends=(cowsay)
source=("arjen.cow"
        "LICENSE")
sha256sums=('08e079da5378c33915dacef67834dd7d10e74715aa0dcc0d2db2f6e007155ac3'
            '3972dc9744f6499f0f9b2dbf76696f2ae7ad8af9b23dde66d6af86c9dfb36986')

package() {
	install -D LICENSE $pkgdir/usr/share/arjensay/LICENSE
	install -D arjen.cow $pkgdir/usr/share/cows/arjen.cow
}
