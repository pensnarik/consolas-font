pkgname=consolas-fonts
pkgver=1.0
pkgrel=1
pkgdesc="Consolas fonts"
arch=(any)
depends=(fontconfig xorg-font-utils)
source=("https://github.com/pensnarik/$pkgname/raw/master/consolas-fonts-tts.tar.bz2")
install=$pkgname.install
md5sums=('605c08cc35295126c9ef4b8bdc1b34c4')

package() {
  install -dm 755 "${pkgdir}"/usr/share/fonts/TTF
  install -Dm644 *.ttf "$pkgdir"/usr/share/fonts/TTF
}