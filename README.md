# Vagrant.Knowledge

# Packaging - Save Changes to a box:
Guide:
- https://www.webfoobar.com/node/52

Doc:
- https://developer.hashicorp.com/vagrant/docs/providers/virtualbox/boxes

## Hypervisor: Libvirt KVM
requires: libguestfs-tools. Otherwise it will fail.

example:
```vagrant package --output ubuntu-gnome-minimal.box```
