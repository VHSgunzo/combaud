# Maintainer: VHSgunzo <vhsgunzo.github.io>
pkgname='combaud'
pkgver='0.4'
pkgrel='1'
pkgdesc='Broadcasting audio output from applications to a virtual microphone'
arch=('any')
url='https://github.com/VHSgunzo/combaud'
license=('MIT')
depends=('pipewire' 'grep' 'sed' 'coreutils' 'libpulse' 'gawk')
makedepends=('git')
provides=("$pkgname")
conflicts=("${provides[@]}" "${pkgname}-git")
source=('combaud' 'LICENSE')
sha256sums=('SKIP' 'SKIP')

package() {
    install -Dm755 'combaud' "$pkgdir/usr/bin/combaud"
    install -Dm644 'LICENSE' "$pkgdir/usr/share/licenses/combaud/LICENSE"
}
