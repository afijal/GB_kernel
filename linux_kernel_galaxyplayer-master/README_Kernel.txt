HOW TO BUILD KERNEL 2.6.35 FOR YP-GB1

1. Visit http://www.codesourcery.com/, download and install Sourcery G++ Lite 2009q3-68 toolchain for ARM EABI.

2. Extract kernel source and move into the top directory.

3. Execute 'make palladio_usa_defconfig'.

4. Execute 'make' or 'make -j<n>' where '<n>' is the number of multiple jobs to be invoked simultaneously.

5. If the kernel is built successfully, you will find following files from the top directory:
	arch/arm/boot/zImage
	crypto/ansi_cprng.ko
	drivers/bluetooth/bthid/bthid.ko
	drivers/net/wireless/bcm4329/dhd.ko
	drivers/scsi/scsi_wait_scan.ko
	drivers/samsung/fm_si4709/Si4709_driver.ko
	drivers/misc/vibetonz/vibrator.ko
