# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-krasnoyarsk
pkgver=70
pkgrel=1
pkgdesc="Map of Krasnoyarsk for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Krasnoyarsk-${pkgver}.orig.zip")
md5sums=('981aba14da26079b423b35db21205637')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Krasnoyarsk.dgdat "${startdir}/pkg/opt/2gis/krasnoyarsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Krasnoyarsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Krasnoyarsk.dglf" || return 1
     
}

