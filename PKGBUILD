# Maintainer: absent

pkgname=python2-bidi
pkgver=0.3.4
pkgrel=1
pkgdesc="Bi-directional (BiDi) layout implementation in pure python"
arch=(any)
url="https://github.com/MeirKriheli/python-bidi"
license=('LGPLv3')
depends=('python2')
source=("https://github.com/MeirKriheli/python-bidi/archive/v${pkgver}.zip")
md5sums=('435df323612b7ec8c90fd0828d816ccd')

package() {
  cd "${srcdir}/python-bidi"-${pkgver}
  python2 setup.py install --root="${pkgdir}/"
}
