pkgname=2gis-nizhnevartovsk
pkgver=87
pkgrel=1
pkgdesc="Map of Nizhnevartovsk for 2GIS, August 2013"
arch=('i686' 'x86_64')
url="http://nizhnevartovsk.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.5.1')
source=("http://download.2gis.ru/arhives/2GISData_Nizhnevartovsk-87.orig.zip")
md5sums=('f2893608855912ed2f3d6269d981d6bd')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Nizhnevartovsk.dgdat" "${pkgdir}/opt/2gis/nizhnevartovsk.dgdat" || return 1
  install -D -m 644 "${srcdir}/2gis/3.0/Plugins/DGisLan/Nizhnevartovsk.dglf" "${pkgdir}/opt/2gis/Plugins/DGisLan/nizhnevartovsk.dglf" || return 1
}
