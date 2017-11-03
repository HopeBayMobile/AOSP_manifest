
# Tera [![Join the chat at https://gitter.im/HopeBayMobile/Lobby](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/HopeBayMobile/Lobby)


## Setup Repository

To initialize your local repository without vender
```
repo init -u https://github.com/HopeBayMobile/AOSP_manifest -b tera/android-7.1.2_r8
```

Get full repositories
```
repo sync
```

Download bullhead vendor 

Get LG and Qualcomm vendor image from [google](https://developers.google.com/android/drivers#bullheadn2g47o)

## Building

* Current only porting to Nexus 5x bullhead

```
. build/envsetup.sh
lunch tera_bullhead-userdebug
make -j8
```

## Note
```
Tera still in development, Any issue are welcome!
You can go to our gitter to find us or other way you find.
```
