# Maintainer : Martin Wimpress <code@flexion.org>

pkgname=networkmanager-dispatcher-ufw
pkgver=1.0
pkgrel=2
pkgdesc="Dispatcher Script for the Uncomplicated Firewall (ufw)"
arch=(any)
license=('MIT')
url="http://www.gnome.org/projects/NetworkManager"
depends=('networkmanager' 'ufw')
backup=(etc/NetworkManager/dispatcher.d/10-ufw)
changelog=ChangeLog
source=("10-ufw")
sha256sums=('654f6c3fc54ab3fe1bdf974b846fd215958074cc89cf54137f8ac22e66238359')

package() {
    install -Dm700 "${srcdir}/10-ufw" "${pkgdir}/etc/NetworkManager/dispatcher.d/10-ufw"
}
