pkgname=2gis-nizhnevartovsk
pkgver=92
pkgrel=1
pkgdesc="Map of Nizhnevartovsk for 2GIS, January 2014"
arch=('i686' 'x86_64')
url="http://nizhnevartovsk.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.11.0')
source=("http://download.2gis.ru/arhives/2GISData_Nizhnevartovsk-92.orig.zip")
md5sums=('08f7169188f0c134457524af385b144a')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Nizhnevartovsk.dgdat" "${pkgdir}/opt/2gis/nizhnevartovsk.dgdat" || return 1
  
}
