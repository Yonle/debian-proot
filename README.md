[![Debian Linux](https://www.debian.org/Pics/homeworld-fg.png)](https://debian.org)
# debian-proot 
A fork of [Yonle/alpine-proot](https://github.com/Yonle/alpine-proot) (github). A well quick standalone Debian PRoot installer & launcher. Also works for every architectures, Linux distros, and even in **__[Termux](https://termux.org)__**.

Debian-proot support both [Plain PRoot](https://github.com/proot-me/proot) and [proot-rs (Rust)](https://github.com/proot-me/proot-rs). If you have both proot and proot-rs installed, but you want to use proot-rs instead to launch debian-proot, simply set [`DEBIANPROOT_USE_PROOT_RS`](https://github.com/Yonle/debian-proot/wiki/Environment-Variables#debianproot_use_proot_rs) as `true`.

## Installation
```sh
curl -Lo debian-proot.sh git.io/debian-proot.sh
chmod +x debian-proot.sh 

# To launch debian-proot anytime, simply do:
./debian-proot.sh
```
It's very recommended to use [this](https://github.com/termux/proot) proot fork since this fork has a lot of fix & feature implemented *(P.S. This proot fork also works on other than Termux)*

For more information about debian-proot, please check the debian-proot [wiki](https://github.com/Yonle/debian-proot/wiki).
## Sound support
In order to make this works, **__PulseAudio__** should be installed at host system. At startup, the script automatically launch PulseAudio server in non-system mode if there is no pulse UNIX socket detected.. However, in [debian-proot](https://github.com/Yonle/debian-proot), sound support is already ready-to-use at startup as long you have PulseAudio installed on the host system.

## Online Debian-proot
*( Unavailable yet )*

## Community
- Discord Server: https://discord.gg/9S3ZCDR

## Sources
- PRoot: https://proot-me.github.io
- Debian: https://debian.org
