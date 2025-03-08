# Install ubuntu custom

```bash 
xorriso -as mkisofs -r -V "Name of the Image" -o ../ubuntu-24.04.2-desktop-amd64_custom_iso.iso -J -l -b boot/grub/i386-pc/eltorito.img -c boot.catalog -no-emul-boot -boot-load-size 4 -boot-info-table ubuntu-24.04.2-desktop-amd64/
```bash