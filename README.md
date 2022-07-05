# QEMU-on-Old-Mac
Footprints being made to have my old MacBook Pro (Mid 2012) to run Win11 as Guest OS on `QEMU`

## Prerequisites (Base Data)
Windows 11 Image (ISO or Hyper-V format) to be converted to `QCONV2` like:

`
qemu-img convert -f raw ./Downloads/Windows11_InsiderPreview_Client_ARM64_en-us_25140.VHDX -O qcow2 W11ARM.qcow2
`
