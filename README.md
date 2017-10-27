# alpine-kvm

![](https://img.shields.io/badge/STATE-work%20in%20progress-orange.svg)

## Description

A lightweight and minimal system tailored for KVM (via libvirt).

## Quick how-to (as a temporary reminder)


```bash
$ apk add qemu-system-x86_64 libvirt-qemu dbus
$ rc-update add libvirt
$ rc-update add dbus
```

Edit **/etc/libvirt/libvirtd.conf** to enable remote authentication, then add the group **libvirt** to the user.


## TODO

- [ ] Finalize QEMU integration
- [ ] Save configuration changes on shutdown (detect changes then re-create the apkvol)
- [ ] Write documentation (build, workflow with docker, ...)
