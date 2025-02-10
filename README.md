arch section:

install packages: sudo pacman -S [package name]

install packages via AUR (arch user repository): paru -S [package name] (if using yay or some other aur manager replace paru with that) (i also reccomend paruz, a tui for paru)

approve pkgbuild on paru: press q on keyboard

start bluetooth: systemctl start bluetooth.service

remove packages: replace -S in either pacman or aur manager with -R

if you get errors with a package install, replace -S with -Syu
