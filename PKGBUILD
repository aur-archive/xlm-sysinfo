# Manteiner: Elia Notarangelo < elia dot notarangelo at gmail dot com>
# Contributor: paky <pascoc@tiscali.it>

pkgname=xlm-sysinfo
pkgver=0.0.4
pkgrel=1
pkgdesc="a gambas tool for system informations"
arch=('any')
url="http://www.xfce-italia.it/index.php?topic=799.0"
license=('GPL')
depends=('gambas2-runtime' 'gambas2-gb-qt' 'gambas2-gb-form' 'sudo' 'gksu' 'lshw')
source=("http://master.dl.sourceforge.net/project/archmind/xlm-sysinfo/$pkgname-$pkgver.tar.gz")


build() {
	cd ${srcdir}/${pkgname}-${pkgver}

	BIN_DIR=${pkgdir}/usr/bin
	DOC_DIR=${pkgdir}/usr/share/doc/${pkgname}
	DESK_DIR=${pkgdir}/usr/share/applications
	MENU_DIR=${pkgdir}/usr/share/menu
	ICON_DIR=${pkgdir}/usr/share/pixmaps
	

	install -d ${BIN_DIR} ${DOC_DIR} ${MENU_DIR} ${ICON_DIR} ${DESK_DIR}


	install -D Xlm-Sysinfo.gambas ${BIN_DIR}
	install -D copyright ${DOC_DIR}
	install -D xlm-sysinfo.desktop ${DESK_DIR}
	install -D xlm-sysinfo.menu ${MENU_DIR}
	install -D xlm-sysinfo.png ${ICON_DIR}
	
}

md5sums=('0fc0ce9e8fd002238b686642fc8a029e')
