# fresh-disk
an installer script for installing a fresh luks encrypted debian beside an existing debian install. 

point fresh-disk to a boot partition, root partition, and usb key, then
```bash
./install
```
will do the rest. 

# features
    * encrypts root partition with cbc mode aes 256
    * automatically adds the debian install to grub
    * encrypt the root partition by pluggin in your usb key at start up
