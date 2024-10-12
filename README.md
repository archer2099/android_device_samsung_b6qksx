# TWRP Device Tree for Samsung Galaxy Z Fold6 5G (Korean version)

## For Decryption
[Userdata_AIO](https://xdaforums.com/t/sm-f741b-0-userdata_aio-odin-flashable-to-automatically-remove-encryption-make-rom-rw-install-twrp-root-use-on-stock-firmware-unlocked-bootloaders.4689221/)

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/archer2099/android_device_samsung_b6qksx device/samsung/b6q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_q6q-eng
mka recoveryimage
```
