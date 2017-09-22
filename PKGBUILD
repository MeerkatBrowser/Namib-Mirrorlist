pkgname=namib-mirrorlist
pkgver=0.0.1
pkgrel=1
pkgdesc="Namib GNU/Linux mirror list for use by pacman"
arch=('any')
url="https://github.com/MeerkatBrowser/Namib-Repository/"
license=('GPL')
backup=(etc/pacman.d/namibmirror)
source=(namibmirror)


package() {
  mkdir -p $pkgdir/etc/pacman.d
  install -m644 $srcdir/namibmirror $pkgdir/etc/pacman.d/
}

md5sums=('6f6ba5f42521b5f47666040b08b3a065')


