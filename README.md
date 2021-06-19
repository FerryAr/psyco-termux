psyco-termux
=============
Termux packages from master branch of [termux-packages](https://github.com/termux/termux-packages) repository for Android 5 API 21 arm

## Installation
1. Add gpg key : `wget -qO - https://raw.githubusercontent.com/FerryAr/psyco-termux/main/ferryar.gpg | apt-key add -`
2. Add my repo to sources.list : `echo deb https://ferryar.github.io/psyco-termux 21 main >> $PREFIX/etc/apt/sources.list`
3. apt update && apt upgrade

## Note :
- I just build essential package, you can request package for me to build, but make sure that's package is available on termux-packages repo
- Some packages is can't be build, even after I applied patch from android-5 branch
- I manually build those packages, and I may unable to fulfill your request if the package is too big.

### Packages that requires more work (help needed!)
- procps
- proot
- mariadb
- openssh
- krb5
- pulseaudio (sles didn't work)
