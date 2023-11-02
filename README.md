# HorizonDroid

 Getting Started
---------------
To get started with the HorizonDroid sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/HorizonDroidLab/manifest.git -b fourteen
```

Then sync up:

```bash
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j8
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch aosp_devicecodename-buildtype
```

Start compilation

```bash
make bacon
```
-----------------------------------------------------------------------------
Credits:
=======
 * [**CAF**](https://source.codeaurora.org)
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelOS**](https://github.com/PixelOS-Fourteen)
 * [**DroidX-UI**](https://github.com/DroidX-UI)
 * [**AfterlifeOS*](https://github.com/AfterLifePrjkt13)
-----------------------------------------------------------------------------
