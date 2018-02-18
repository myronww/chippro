# Chip Pro Notes

## Chip Pro Flashing

### sunxi
![Sunxi Wiki](http://linux-sunxi.org/Main_Page)

### sunxi-fel
*sunxi-fel* is a binary application that is used to connect with *AllWinner* CPUs FEL protocol

![Sunxi Wiki - FEL](http://linux-sunxi.org/FEL)

The following line of code is taken from a *ChipPro* flashing script.  It is the first step in flashing a *Chip Pro* device.

```bash
sunxi-fel uboot ${BR_OUTPUT_DIR}/images/u-boot-sunxi-with-spl.bin write 0x43100000 ${BR_OUTPUT_DIR}/images/uboot.script
```

Site Containing Info on "AllWinner" CPUs
    sudo apt-get install gcc-arm-linux-gnueabihf
