pkgname=consolas-fonts
pkgver=1.0
pkgrel=1
pkgdesc="Consolas fonts"
arch=(any)
depends=(fontconfig xorg-font-utils)
source=("http://someurl.org/$pkgname.tar.bz2")
install=$pkgname.install

package() {
  install -Dm644 $pkgname/Consolas-Bold.ttf "$pkgdir"/usr/share/fonts/TTF/Consolas-Bold.ttf
  install -Dm644 $pkgname/Consolas-Regular.ttf "$pkgdir"/usr/share/fonts/TTF/Consolas-Regular.ttf
}