Fuse Settings:

Ext, Hi, Lo : FE DA EF
Lock: EF

During operation at low voltages (i.e. < 3V3), the clock needs to be scaled back to i.e. 2Mhz.
Do this in software, *not* in the fusebits. This is to continue allowing the USB bootloader.
