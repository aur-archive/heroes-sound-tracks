# Maintainer: Hubert Maraszek <marach5 at gmail dot com>
pkgname=heroes-sound-tracks
pkgver=1.0
pkgrel=1
pkgdesc="An advanced Nibbles clone"
arch=('any')
url="http://heroes.sourceforge.net/"
license=('GPL')
source=(http://prdownloads.sourceforge.net/heroes/$pkgname-$pkgver.tar.gz)
md5sums=('bcde6137a4b21b7395fd3d84b42b7888')

build() {
  cd "$srcdir/$pkgname-$pkgver"

  ./configure --prefix=/usr
}

package() {
  cd "$srcdir/$pkgname-$pkgver"

  make DESTDIR="$pkgdir/" install
}

# vim:set ts=2 sw=2 et:
