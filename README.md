# os
a command-line tool to get os info.

## os command usage
|command|values|
|-|-|
|`os -h`  |help of this command|
|`os -V`  |version of this command|
|`os`     |all info|
|`os kind`|`linux` `darwin` `windows` `freebsd` `nstbsd` `openbsd`|
|`os type`|`android` `debian` `ubuntu` `centos` `fedora` `arch` `manjaro` `gentoo` `apline` `void`|
|`os name`|`Android` `macOS` `FreeBSD` `NetBSD` `OpenBSD` `Debian` `Ubuntu` `CentOS` `Fedora`|
|`os vers`||
|`os arch`|`x86_64` `amd64` `aarch64`|
|`os libc`|`glibc` `musl` `bionic`|
|`os subs`|`cygwin` `msys` `mingw32` `mingw64` `termux`|

## common used os list
|kind|type|name|libc|sys-pkg|subs|sub-sys-pkg|
|-|-|-|-|-|-|-|
|`linux`|`android`|[Andriod](https://www.android.com/)|`bionic`||[termux](https://termux.com/)|[pkg](https://wiki.termux.com/wiki/Package_Management)|
|`linux`|`debian`|[Debian GNU/Linux](https://www.debian.org/releases/)|`glibc`|[apt-get](https://manpages.debian.org/buster/apt/apt-get.8.en.html)|||
|`linux`|`ubuntu`|[Ubuntu](https://releases.ubuntu.com/)|`glibc`|[apt-get](http://manpages.ubuntu.com/manpages/cosmic/man8/apt-get.8.html)|||
|`linux`|`linuxmint`|[LinuxMint](https://linuxmint.com/)|`glibc`|[apt-get](https://community.linuxmint.com/tutorial/view/588)|||
|`linux`|`centos`|[CentOS](https://www.centos.org/centos-linux/)|`glibc`|[yum](http://yum.baseurl.org/) [dnf](https://github.com/rpm-software-management/dnf)|||
|`linux`|`fedora`|[Fedora](https://getfedora.org/)|`glibc`|[yum](http://yum.baseurl.org/) [dnf](https://github.com/rpm-software-management/dnf)|||
|`linux`|`opensuse-leap`|[openSUSE Leap](https://get.opensuse.org/leap)|`glibc`|[zypper](https://en.opensuse.org/Portal:Zypper)|||
|`linux`|`alpine`|[AlpineLinux](https://alpinelinux.org/)|`musl`|[apk](https://docs.alpinelinux.org/user-handbook/0.1a/Working/apk.html)|||
|`linux`|`void`|[VoidLinux](https://voidlinux.org/)|`glibc`|[xbps](https://github.com/void-linux/xbps/)|||
|`linux`|`void`|[VoidLinux](https://voidlinux.org/)|`musl`|[xbps](https://github.com/void-linux/xbps/)|||
|`linux`|`arch`|[ArchLinux](https://archlinux.org/)|`glibc`|[pacman](https://wiki.archlinux.org/index.php/pacman)|||
|`linux`|`manjaro`|[Manjaro](https://manjaro.org/)|`glibc`|[pacman](https://wiki.manjaro.org/index.php?title=Pacman_Overview)|||
|`linux`|`gentoo`|[Gentoo](https://www.gentoo.org/)|`glibc`|[Portage](https://wiki.gentoo.org/wiki/Portage)|||
|`freebsd`|`freebsd`|[FreeBSD](https://www.freebsd.org/)||[pkg](https://github.com/freebsd/pkg)|||
|`openbsd`|`openbsd`|[OpenBSD](https://www.openbsd.org/)||[pkg_*](https://www.openbsdhandbook.com/package_management/)|||
|`netbsd`|`netbsd`|[NetBSD](https://www.netbsd.org/)||[pkgin](https://pkgin.net/)|||
|`darwin`|`macos`|[macOS](https://www.apple.com/macos)||[HomeBrew](https://brew.sh/)|||
|`windows`|`windows`|[Windows](https://www.microsoft.com/en-us/windows)||[Chocolatey](https://chocolatey.org/)|[cygwin](https://www.cygwin.com/)|[Chocolatey](https://chocolatey.org/)|
|`windows`|`windows`|[Windows](https://www.microsoft.com/en-us/windows)||[Chocolatey](https://chocolatey.org/)|[msys](https://www.msys2.org/)|[pacman](https://www.msys2.org/docs/package-management/)|
|`windows`|`windows`|[Windows](https://www.microsoft.com/en-us/windows)||[Chocolatey](https://chocolatey.org/)|[mingw32](https://www.msys2.org/)|[pacman](https://www.msys2.org/docs/package-management/)|
|`windows`|`windows`|[Windows](https://www.microsoft.com/en-us/windows)||[Chocolatey](https://chocolatey.org/)|[mingw64](https://www.msys2.org/)|[pacman](https://www.msys2.org/docs/package-management/)|
