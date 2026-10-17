## ZFSBootMenu build config files with ssh remote access

Copy vmlinuz.EFI to /boot/efi/EFI/BOOT/BOOTX64.EFI

default ssh port is 2222
root_key - ssh public key

```
/etc/dropbear -> root_key  ssh_host_ecdsa_key ssh_host_rsa_key
```
```
/etc/cmdline.d -> dracut-network.conf "
```
