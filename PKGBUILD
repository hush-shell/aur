# Maintainer: gahag <gabriel.s.b@live.com>
#
# This PKGBUILD was generated by `cargo aur`: https://crates.io/crates/cargo-aur

pkgname=hush-bin
pkgver=0.1.2
pkgrel=1
pkgdesc="Hush is a unix shell scripting language based on the Lua programming language"
url="https://github.com/gahag/hush"
license=("MIT")
arch=("x86_64")
provides=("hush")
conflicts=("hush")
source=("https://github.com/gahag/hush/releases/download/v$pkgver-alpha/hush-$pkgver-x86_64.tar.gz")
sha256sums=("41142b92082c3eca385e98e0b619a1f38f9c6dbb8c426026beea4c0414e8429d")

package() {
    install -Dm755 hush -t "$pkgdir/usr/bin"
    install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
