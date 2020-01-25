<p align="center">
<img src="https://i.postimg.cc/ht3j97Wk/CSBanner-Logo.png" > 

Getting Started
==================================================
>> To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

>> To initialize your local repository, use a command like this:

```bash
    repo init --depth=1 -u git://github.com/CesiumOS/manifest.git -b ten
```

>> Then to sync up:

```bash
     repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Compilation of Cesium OS:
====================
>> From root directory of Project, perform following commands in terminal


```bash
source build/envsetup.sh
lunch cesium_<devicecodename>-userdebug
make bacon -j$(nproc --all)
```
-----------------------------------------	
Getting Official Maintainership for CesiumOS
==========================================
>> To get Official Maintainership for CesiumOS you should have a stable device source with all the main components working.

>> First make an unofficial build of CesiumOS and post in [**XDA**](xda-developers.com).

>> Then, Ping us on Telegram :- [**bunnyy**](https://t.me/bun_nyy) or [**Sahil**](https://t.me/SahilSonar) 

>> Join our [**Telegram Channel**](https://t.me/cesiumos_channel) and our  [**Telegram group**](https://t.me/cesiumos_official)

>> To publish builds use our Template : [**CesiumOS XDA Template**](https://github.com/CesiumOS/CesiumOS-Template)

<p align="center">
<img src="https://i.postimg.cc/ht3j97Wk/CSBanner-Logo.png" > 




