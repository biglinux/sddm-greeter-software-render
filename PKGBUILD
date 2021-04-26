# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=sddm-greeter-software-render
pkgver=1.0.0
pkgrel=0
arch=('any')
license=('GPL')
url="https://github.com/biglinux/sddm-greeter-software-render"
pkgdesc="Force sddm-greeter to use software render"
depends=('sddm')
source=("git+https://github.com/biglinux/sddm-greeter-software-render.git")
md5sums=(SKIP)

package() {
    cp -r "${srcdir}/sddm-greeter-software-render/sddm-greeter-software-render/usr/" "${pkgdir}/"
} 
