# helium-copr (archived)

**This project is no longer maintained.**

The Helium developers now have their own official Fedora repo:
https://copr.fedorainfracloud.org/coprs/imput/helium/

Please use that one instead.

## How to switch

Run these commands:

```
sudo dnf remove helium
sudo dnf copr remove v8v88v8v88/helium
sudo dnf copr enable imput/helium
sudo dnf install helium-bin
```

Note: the official package is called `helium-bin`, not `helium`.

Thanks to everyone who used this repo!
