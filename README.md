Copy from https://android.googlesource.com/platform/system/core/+/android-7.1.1_r22/toolbox/r.c

This file need to enable the defconfig:
CONFIG_DEVMEM=y
CONFIG_DEVKMEM=y

Make and Install
1. Download it
2. copy to external
3. make r_mem
4. adb push xxxx/r_mem /system/bin/

Usage:
	TODO
