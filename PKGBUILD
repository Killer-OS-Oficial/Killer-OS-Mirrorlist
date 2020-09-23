pkgname=killer-os-mirrorlist
pkgver=stable
pkgrel=2
pkgdesc="Killer-OS mirrorlist"
arch=('x86_64')
url="https://github.com/Killer-OS-Oficial/Killer-OS-Mirrorlist"
license=('GPL3')
backup=(etc/pacman.d/killer-mirrorlist)
source=('killer-os-mirrorlist')
sha256sums=('SKIP')

package() {
  mkdir -p ${pkgdir}/etc/pacman.d
  install -Dm644 ${srcdir}/${source} ${pkgdir}/etc/pacman.d/
}
