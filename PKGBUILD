# Maintainer: VHSgunzo <vhsgunzo.github.io>
pkgname='combaud'
pkgver='1.0'
pkgrel='1'
pkgdesc='Broadcasting audio output from applications to a virtual microphone'
arch=('any')
url='https://github.com/VHSgunzo/combaud'
license=('MIT')
depends=('pipewire' 'grep' 'sed' 'coreutils' 'libpulse' 'gawk')
makedepends=('git')
provides=("$pkgname")
conflicts=("${provides[@]}" "${pkgname}-git")
source=('combaud' 'LICENSE' 'loop-ignore.list')
sha256sums=('SKIP' 'SKIP' 'SKIP')

package() {
    install -Dm755 'combaud' "$pkgdir/usr/bin/combaud"
    install -Dm644 'LICENSE' "$pkgdir/usr/share/licenses/combaud/LICENSE"
    install -Dm644 'loop-ignore.list' "$pkgdir/etc/combaud/loop-ignore.list"
}
