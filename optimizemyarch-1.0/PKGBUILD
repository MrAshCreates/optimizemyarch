# Maintainer: Asher Winstead asher@mrashcreates.xyz
pkgname=optimizemyarch
pkgver=1.0
pkgrel=1
pkgdesc="A script to optimize and maintain Arch Linux installations"
arch=('any')
url="https://github.com/MrAshCreates/optimizemyarch"
license=('MIT')
depends=('bash')
source=("optimizemyarch.sh")
sha256sums=('39bfb476971b62800077315077a8a0bf574a4ac3b29ce51c13186ce26caddd82')

package() {
    install -Dm755 optimizemyarch.sh "$pkgdir/usr/bin/oma"
}
