pkgname=namib-mirrorlist
pkgver=18.06
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

md5sums=('6141c2c9a06508a5f1ee1c19b9df0000')


