# Contributor : Daniel Leining <daniel@the-beach.co>
# Maintainer: Pierre Schiltz <mysti57155@gmail.com>
pkgname=cinnamon-theme-holo
pkgver=3
pkgrel=1
pkgdesc="Android Holo theme for cinnamon"
arch=('any')
url="http://cinnamon-spices.linuxmint.com/themes/view/122"
license=('unknown')
depends=('cinnamon')
source=('http://cinnamon-spices.linuxmint.com/uploads/themes/7CSU-8U0N-BX17.zip')
md5sums=('1d305f2f0c49c6e2f85d942f41f1e2cf')

package() {
  mkdir -p ${pkgdir}/usr/share/themes/
  chmod 777 ${srcdir}/Open_me/Android_Holo
  chmod 777 ${srcdir}/Open_me/Android_Holo/cinnamon
  chmod 777 ${srcdir}/Open_me/Android_Holo_arrow
  chmod 777 ${srcdir}/Open_me/Android_Holo_arrow/cinnamon
  cp -r ${srcdir}/Open_me/Android_Holo ${pkgdir}/usr/share/themes/
  cp -r ${srcdir}/Open_me/Android_Holo_arrow ${pkgdir}/usr/share/themes/
}

