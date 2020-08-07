# Maintainer: Matthias gatto <matthias.gatto@outscale.com>
# Reference: PKGBUILD(5)

pkgname=aliyun-python-sdk-vpc
pkgver=3.0.10
pkgrel=1
pkgdesc='The vpc module of Aliyun Python sdk'

arch=('any')
url='https://github.com/aliyun/aliyun-openapi-python-sdk/'
license=(BSD)

makedepends=('python-pip')

package() {
	PIP_CONFIG_FILE=/dev/null pip install --isolated --root="$pkgdir" --ignore-installed --no-deps aliyun-python-sdk-vpc
}
