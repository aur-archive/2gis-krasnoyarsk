pkgname=2gis-krasnoyarsk
pkgver=103
pkgrel=1
pkgdesc="Map of Krasnoyarsk for 2GIS, March 2014"
arch=('i686' 'x86_64')
url="http://krasnoyarsk.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.11.0')
source=("http://download.2gis.ru/arhives/2GISData_Krasnoyarsk-103.orig.zip")
md5sums=('a8bd3a60a177cdf5b78ee0c6cd8f9606')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Krasnoyarsk.dgdat" "${pkgdir}/opt/2gis/krasnoyarsk.dgdat" || return 1
  
}
