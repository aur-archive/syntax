# Maintainer: Matthias Dietrich <matze_holz@web.de>
pkgname=syntax
pkgver=2.6
pkgrel=2
pkgdesc="Administrative accounting software for self-employed people and 'Nichtbilanzierer'. Jameica-plugin."
arch=('i686' 'x86_64')
url="http://www.willuhn.de/projects/syntax/"
license="GPL"
depends=('java-runtime>=1.6' 'jameica>=2.6')
makedepends=(unzip)
install=syntax.install
source=(http://www.willuhn.de/projects/syntax/releases/$pkgver/$pkgname.zip)
md5sums=('6de7bc56e24ac29b85ce705cc6faf8ef')

build() {
  mkdir -p $pkgdir/opt/jameica/plugins
  cd $srcdir
  cp -r $pkgname $pkgdir/opt/jameica/plugins
}
