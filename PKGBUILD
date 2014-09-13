# Maintainer: Lucid Systemes

pkgname=lucidmkiso
pkgver=1
pkgrel=1
pkgdesc="Tools for creating LuicdSystems live and install iso images"
arch=('any')
url="https://github.com/KaneVanguard/lucidmkiso"
license=('GPL')
depends=('archiso')

package() {
  cd "$pkgdir"
  install -Dm755 "$srcdir/usr/bin/luicdmkiso" usr/bin/luicdmkiso
}
