# Maintainer: Terry Burton <tez at terryburton dot co dot uk>

pkgname=postscriptbarcode
pkgver=0.0.0
pkgrel=1
pkgdesc='Barcode Writer in Pure PostScript'
arch=('any')
arch=('i686' 'x86_64')
#arch=('any')
url='https://github.com/bwipp/postscriptbarcode'
license=('MIT')
depends=('')
makedepends=('ghostscript')
source=("${pkgname}-${pkgver}.tar.gz")
sha256sums=('SKIP')

build() {
  cd "${pkgname}-${pkgver}"
  make -j `nproc`  
}

check() {
  cd "${pkgname}-${pkgver}"
  make test
}

package() {
  cd "${pkgname}-${pkgver}"
}