# SW1

**This repository has the latest configuration files necessary to build OpenPower code for a Swift system:**
* swift_defconfig (used by 'op-build' repo)
* swift.config (used by 'hostboot' repo)

## Building a Swift Image

To build an image for a Swift system:

```
git clone --recursive <wherver this repo ends up>
cd SW1  <or whatver we call it>
./setup_swift
cd op-build
. op-build-env && ./op-build swift_defconfig && ./op-build
```

> See https://github.com/open-power/op-build/blob/master/README.md for more information.

