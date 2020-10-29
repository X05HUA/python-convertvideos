# Maintainer: Tim Schumacher <timschumi@gmx.de>
# Contributor: Felix Yan <felixonmars@archlinux.org>
# Contributor: Gordian Edenhofer <gordian.edenhofer[at]yahoo[dot]de>

pkgname=python-helloworld
pkgver=0.1
pkgrel=1
pkgdesc="Hook and simulate keyboard events on Windows and Linux"
arch=('any')
license=('Apache2')
url="https://github.com/dbarnett/python-helloworld"
depends=('python-setuptools')
source=("git+$url")
sha512sums=('SKIP')

build() {
  cd python-helloworld
  python setup.py build
}

package() {
  cd python-helloworld
  python setup.py install --root="$pkgdir" --optimize=1
}
