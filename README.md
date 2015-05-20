Tetra (Sony SmartWatch 3) Kernel Builds:
========================================

You need:

* This repo checked out in your home directory.
  To build a specific release checkout that release tag (e.g. r1).

* http://github.com/crpalmer/android-kernel-build-tools
  (branch master checked out in your home directory)

* http://github.com/crpalmer/android_kernel_sony_tetra
  To build a specific release checkout that release tag (e.g. r1).

And then run

~/android-kernel-build-tools/build-prebuilt.sh ~/tetra-kernel-build-configs/LWX49K

which will generate a boot.img in /data/tetra/kernel.out.

Note: You may need to update the CROSS_COMPILE parameter to match your toolchain.
