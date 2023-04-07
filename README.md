## My libvirt config

not the best, not the cleanest, but it works<br>using virt-manager

### Features
- gpu passthrough with ROM file (GT 1030);
- cpu pinning (6 threads of a Ryzen 5 3600x);
- EAC VM detection bypass (using smbios);
- some custom hooks;
- Solidworks VM detection bypass;
- etc.

### File locations

- `10ferestre.xml`: `/etc/libvirt/qemu/`
- `qemu`: `/etc/libvirt/hooks/`
- `patch.rom`: `/var/lib/libvirt/vbios/`<br>ROM from TechPowerUp, works with ASUS GT 1030
- `virtio-win-0.1.229.iso`: `/var/lib/libvirt/images/`