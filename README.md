Building Mingw for Android
==========================

The `build.sh` script in this directory is used to build mingw for Android.

Mingw is built from the `mingw` branch of AOSP. To fetch the sources:

```bash
repo init -u https://android.googlesource.com/platform/manifest -b mingw

# Googlers, use
repo init -u \
    persistent-https://android.git.corp.google.com/platform/manifest -b mingw
```

To build, run `build.sh`. Run with `--help` for a list of options.
