<p align="center">
<img src="https://i.postimg.cc/ZYXGkXdr/About-Device-Banner-2.png" > 

CesiumOS v4.x
==================================================

#### This release is based on android-13.0.0-rel

Getting Started
==================================================

```bash
      $ mkdir ~/cesium
      $ cd ~/cesium
```

##### Initializing the cos repo and downloading the manifest

```bash
      $  repo init -u https://github.com/CesiumOS-org/manifest.git -b tiramisu-rel
```

##### Syncing the source
>> [Hint: This might take a long time as the source is ~70GB]

```bash
      $  repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

##### To build CesiumOS ROM

```bash
      $ cd ~/cesium
      $ source build/envsetup.sh
      $ lunch <devicecodename>-user
      $ m bacon | tee build.log
```