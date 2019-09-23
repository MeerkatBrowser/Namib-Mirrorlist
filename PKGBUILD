pkgname=namib-mirrorlist
pkgver=19.09
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

md5sums=('a29d28c5d2f4dca1555ec990c388c142')


