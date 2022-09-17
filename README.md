## Recovery Device Tree for the Samsung Galaxy A33 5G (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a33x-eng
make recoveryimage
```

Kernel source:
https://github.com/rmnhg/android_kernel_samsung_a33x
