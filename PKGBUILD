pkgname=xfwm4-void-theme
pkgver=0.0.1
pkgrel=1
pkgdesc="a border only theme for xfwm4"
arch=('any')
depends=('xfwm4')
url='https://github.com/aoaaceai/xfwm4-void-theme'
source=("$url/archive/refs/tags/v$pkgver.tar.gz")
license=('unknown')
sha256sums=('9990fcc4d594f28ee81a1debdbccb0b778dc5488864e5f53a67db0a9708612a7')

package() {
    cd "$pkgname-$pkgver"
    install -dm755 xfwm4 "$pkgdir/usr/share/themes/VOID/xfwm4"
}
