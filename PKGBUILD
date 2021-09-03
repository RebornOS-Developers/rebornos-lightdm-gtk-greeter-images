pkgname=rebornos-lightdm-gtk-greeter-images
pkgver=1.0
pkgrel=1.5
pkgdesc="RebornOS images used in lightdm-gtk-greeter"
arch=('any')
url="https://gitlab.com/rebornos-team/rebornos-special-system-files/rebornos-lightdm-gtk-greeter-images"
license=('GPL3')
source=('avatar.png' 
        'rebornos.jpg')
sha256sums=('9fc5ed4230af150ec9fa220a809d4c19cd5a49160465b7377d54e6bda5414aae'
            '9eeb87a4e145f7ea0b6ae85a7c917f5028d00cb6ad280e66e5fb4390021373ec')

package() {
  mkdir -p ${pkgdir}/usr/share/pixmaps
  install -Dm644 ${srcdir}/avatar.png ${pkgdir}/usr/share/pixmaps/
  install -Dm644 ${srcdir}/rebornos.jpg ${pkgdir}/usr/share/pixmaps/
}

