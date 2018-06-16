# Maintainer: David Ford <david@blue-labs.org>
pkgname=python-pam
pkgver=1.8.4
pkgrel=1
pkgdesc="Linux, FreeBSD, etc (any system that uses PAM) PAM module that provides an
authenticate function given a username, password, and other optional keywords."
arch=('any')
url="https://github.com/FirefighterBlu3/python-pam"
license=('MIT')
depends=('python' 'pam')
makedepends=('python-setuptools')
options=(!emptydirs)
changelog=(ChangeLog)
source=(https://pypi.python.org/packages/source/p/${pkgname}/${pkgname}-${pkgver}.tar.gz)
md5sums=(db71b6b999246fb05d78ecfbe166629d)

package() {
  cd "$pkgname-$pkgver"
  python setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
