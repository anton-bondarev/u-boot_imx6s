u-boot
===================

### Install
install u-boot-tools for Ubuntu
``` sudo apt-get install u-boot-tools ```

### Get sources

#### <i class="icon-file"></i>u-boot 2009.08

``` git clone https://github.com/csdtusur/u-boot_imx6s.git -b 2009.08 ```

#### <i class="icon-hdd"></i>u-boot 2015.04

``` $ git clone https://github.com/csdtusur/u-boot_imx6s.git -b 2015.04 ```

### Prepare
```
$ export ARCH=arm
$ export CROSS_COMPILE=~/gcc-4.6.2-glibc-2.13-linaro-multilib-2011.12/fsl-linaro-toolchain/bin/arm-none-linux-gnueabi-
```
### Configure

``` $ make mx6solo_sabresd_config ```

### Build

``` $ make ```

