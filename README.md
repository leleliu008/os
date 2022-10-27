# os
a command-line tool to get os info.

## os command usage
|command|values|
|-|-|
|`os --help`     |show help of this command|
|`os --version`  |show version of this command|
|`os`     |show all info|
|`os kind`|`windows` `darwin` `freebsd` `netbsd` `openbsd` `linux` `android`|
|`os type`|`windows` `macos` `ios` `tvos` `watchos` `freebsd` `netbsd` `openbsd` `linux` `android`|
|`os uuid`|`windows` `macos` `ios` `tvos` `watchos` `freebsd` `netbsd` `openbsd` `android` `debian` `ubuntu` `centos` `fedora` `arch` `manjaro` `gentoo` `apline` `void`|
|`os name`|`Windows` `macOS` `iOS` `tvOS` `watchOS` `FreeBSD` `NetBSD` `OpenBSD` `Android` `Debian GNU/Linux` `Ubuntu` `CentOS` `Fedora`|
|`os vers`|show version of current os|
|`os arch`|`x86_64` `amd64` `aarch64`|
|`os ncpu`|show the number of cpu of current os|
|`os libc`|`glibc` `musl` `bionic`|
|`os subs`|`cygwin` `msys` `mingw32` `mingw64` `termux`|

## common used os list
|kind|type|uuid|name|libc|sys-pkg|subs|sub-sys-pkg|
|-|-|-|-|-|-|-|-|
|`darwin`|`macos`|`macos`|[macOS](https://www.apple.com/macos)||[HomeBrew](https://brew.sh/)|||
|`linux`|`linux`|`debian`|[Debian GNU/Linux](https://www.debian.org/releases/)|`glibc`|[apt-get](https://manpages.debian.org/buster/apt/apt-get.8.en.html)|||
|`linux`|`linux`|`ubuntu`|[Ubuntu](https://releases.ubuntu.com/)|`glibc`|[apt-get](http://manpages.ubuntu.com/manpages/cosmic/man8/apt-get.8.html)|||
|`linux`|`linux`|`linuxmint`|[LinuxMint](https://linuxmint.com/)|`glibc`|[apt-get](https://community.linuxmint.com/tutorial/view/588)|||
|`linux`|`linux`|`fedora`|[Fedora](https://getfedora.org/)|`glibc`|[yum](http://yum.baseurl.org/) [dnf](https://github.com/rpm-software-management/dnf)|||
|`linux`|`linux`|`centos`|[CentOS](https://www.centos.org/centos-linux/)|`glibc`|[yum](http://yum.baseurl.org/) [dnf](https://github.com/rpm-software-management/dnf)|||
|`linux`|`linux`|`rocky`|[RockyLinux](https://rockylinux.org/)|`glibc`|[yum](http://yum.baseurl.org/) [dnf](https://github.com/rpm-software-management/dnf)|||
|`linux`|`linux`|`opensuse-leap`|[openSUSE Leap](https://get.opensuse.org/leap)|`glibc`|[zypper](https://en.opensuse.org/Portal:Zypper)|||
|`linux`|`linux`|`alpine`|[AlpineLinux](https://alpinelinux.org/)|`musl`|[apk](https://docs.alpinelinux.org/user-handbook/0.1a/Working/apk.html)|||
|`linux`|`linux`|`void`|[VoidLinux](https://voidlinux.org/)|`musl`|[xbps](https://github.com/void-linux/xbps/)|||
|`linux`|`linux`|`void`|[VoidLinux](https://voidlinux.org/)|`glibc`|[xbps](https://github.com/void-linux/xbps/)|||
|`linux`|`linux`|`arch`|[ArchLinux](https://archlinux.org/)|`glibc`|[pacman](https://wiki.archlinux.org/index.php/pacman)|||
|`linux`|`linux`|`manjaro`|[Manjaro](https://manjaro.org/)|`glibc`|[pacman](https://wiki.manjaro.org/index.php?title=Pacman_Overview)|||
|`linux`|`linux`|`gentoo`|[Gentoo](https://www.gentoo.org/)|`glibc`|[Portage](https://wiki.gentoo.org/wiki/Portage)|||
|`freebsd`|`freebsd`|`freebsd`|[FreeBSD](https://www.freebsd.org/)||[pkg](https://github.com/freebsd/pkg)|||
|`openbsd`|`openbsd`|`openbsd`|[OpenBSD](https://www.openbsd.org/)||[pkg_*](https://www.openbsdhandbook.com/package_management/)|||
|`netbsd`|`netbsd`|`netbsd`|[NetBSD](https://www.netbsd.org/)||[pkgin](https://pkgin.net/)|||
|`windows`|`windows`|`windows`|[Windows](https://www.microsoft.com/en-us/windows)||[Chocolatey](https://chocolatey.org/)|[cygwin](https://www.cygwin.com/)|[Chocolatey](https://chocolatey.org/)|
|`windows`|`windows`|`windows`|[Windows](https://www.microsoft.com/en-us/windows)||[Chocolatey](https://chocolatey.org/)|[msys2](https://www.msys2.org/)|[pacman](https://www.msys2.org/docs/package-management/)|
|`windows`|`windows`|`windows`|[Windows](https://www.microsoft.com/en-us/windows)||[Chocolatey](https://chocolatey.org/)|[mingw32](https://www.msys2.org/)|[pacman](https://www.msys2.org/docs/package-management/)|
|`windows`|`windows`|`windows`|[Windows](https://www.microsoft.com/en-us/windows)||[Chocolatey](https://chocolatey.org/)|[mingw64](https://www.msys2.org/)|[pacman](https://www.msys2.org/docs/package-management/)|
|`android`|`android`|`android`|[Andriod](https://www.android.com/)|`bionic`||[termux](https://termux.com/)|[pkg](https://wiki.termux.com/wiki/Package_Management)|
