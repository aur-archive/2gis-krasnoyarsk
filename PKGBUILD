# Contributor: Nebulosa <nebulosa2007 na yandekse>

pkgname=2gis-krasnoyarsk
pkgver=67
pkgrel=1
pkgdesc="Map of Krasnoyarsk for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Krasnoyarsk-${pkgver}.orig.zip")
md5sums=('98995a20dd58cdd27f16cbbaa46cf3a6')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Krasnoyarsk.dgdat "${startdir}/pkg/opt/2gis/krasnoyarsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Krasnoyarsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Krasnoyarsk.dglf" || return 1

}
