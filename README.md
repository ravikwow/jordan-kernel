Commands for build
export ARCH=arm
export SUBARCH=arm
export CROSS_COMPILE=./arm-eabi-4.4.3/bin/arm-eabi-
make mb526_cm10.1_defconfig
make -j3