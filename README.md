# alpine-kvm
A lightweight and minimal system tailored for KVM (via libvirt).

    Currently a work in progress

# Quick how-to (as a temporary reminder)

```bash
$ apk add qemu-system-x86_64 libvirt-qemu dbus
$ rc-update add libvirt
$ rc-update add dbus
```

Edit **/etc/libvirt/libvirtd.conf** to enable remote authentication, then add the group **libvirt** to the user.
