# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-krasnoyarsk
pkgver=84
pkgrel=1
pkgdesc="Map of Krasnoyarsk for 2GIS, August 2012"
arch=('i686' 'x86_64')
url="http://krasnoyarsk.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.7.0.0')
source=("http://download.2gis.ru/arhives/2GISData_Krasnoyarsk-84.orig.zip")
md5sums=('824ffa687a480710a2501648f82cda2d')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Krasnoyarsk.dgdat "${startdir}/pkg/opt/2gis/krasnoyarsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Krasnoyarsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Krasnoyarsk.dglf" || return 1
     
}

