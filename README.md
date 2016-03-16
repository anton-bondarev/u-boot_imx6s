u-boot
===================


#### <i class="icon-file"></i>u-boot 2009.08

```bash
$ git clone https://github.com/csdtusur/u-boot_imx6s.git -b 2009.08
$ export ARCH=arm
$ export CROSS_COMPILE=~/gcc-4.6.2-glibc-2.13-linaro-multilib-2011.12/fsl-linaro-toolchain/bin/arm-none-linux-gnueabi-
$ export PATH=~/u-boot-2009.08/tools:$PATH
$ make distclean
$ make mx6solo_sabresd_config
$ make
```
#### <i class="icon-hdd"></i>u-boot 2015.04

```
$ git clone https://github.com/csdtusur/u-boot_imx6s.git -b 2015.04
$ export ARCH=arm
$ export CROSS_COMPILE=~/gcc-4.6.2-glibc-2.13-linaro-multilib-2011.12/fsl-linaro-toolchain/bin/arm-none-linux-gnueabi-
$ export PATH=~/u-boot-2015.04/tools:$PATH
$ make distclean
$ make mx6solosabresd_defconfig
$ make
```
