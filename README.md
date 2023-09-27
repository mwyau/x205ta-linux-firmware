# Asus X205TA Linux Firmware
### Usage
- Place in `/lib/firmware/brcm/`
- Reboot
```
% dmesg
...
[   x.xxxxxx] brcmfmac mmc0:0001:1: firmware: direct-loading firmware brcm/brcmfmac43340-sdio.txt
...
[   x.xxxxxx] bluetooth hci0: firmware: direct-loading firmware brcm/BCM43341B0.hcd
[   x.xxxxxx] brcmfmac: brcmf_c_preinit_dcmds: Firmware: BCM43340/2 wl0: Apr 23 2021 05:48:34 version 6.10.190.91 (r728536) FWID 01-d45e96c4
...
```
- Tested in Debian bullseye and bookworm

