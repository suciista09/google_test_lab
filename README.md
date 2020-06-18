# google_test_lab

to change device matrix, simply modify android-matrix.yaml

```
(name of your matrix):
  type: robo
  timeout: (how long you want to crawl your apk)
  device-ids: (device id)
  os-version-ids: (api list)
  locales: en
  ```

Example:

```
google-pixel:
  type: robo
  timeout: 2m
  device-ids: sailfish
  os-version-ids: [27, 28]
  locales: en
  ```
  
Device List :
```
┌───────────────────┬────────────────────┬─────────────────────────────────────┬──────────┬─────────────┬───────────────────┬─────────┐
│      MODEL_ID     │        MAKE        │              MODEL_NAME             │   FORM   │  RESOLUTION │   OS_VERSION_IDS  │   TAGS  │
├───────────────────┼────────────────────┼─────────────────────────────────────┼──────────┼─────────────┼───────────────────┼─────────┤
│ A0001             │ OnePlus            │ OnePlus One                         │ PHYSICAL │ 1920 x 1080 │ 22                │         │
│ FRT               │ HMD Global         │ Nokia 1                             │ PHYSICAL │  854 x 480  │ 27                │         │
│ G8142             │ Sony               │ Sony XPERIA XZ Premium              │ PHYSICAL │ 1920 x 1080 │ 25                │         │
│ G8441             │ Sony               │ Xperia XZ1 Compact                  │ PHYSICAL │ 1280 x 720  │ 26                │         │
│ HWMHA             │ Huawei             │ Huawei Mate 9                       │ PHYSICAL │ 1920 x 1080 │ 24                │         │
│ Nexus10           │ Samsung            │ Nexus 10                            │ VIRTUAL  │ 2560 x 1600 │ 19,21,22          │         │
│ Nexus4            │ LG                 │ Nexus 4                             │ VIRTUAL  │ 1280 x 768  │ 19,21,22          │         │
│ Nexus5            │ LG                 │ Nexus 5                             │ VIRTUAL  │ 1920 x 1080 │ 19,21,22,23       │         │
│ Nexus5X           │ LG                 │ Nexus 5X                            │ VIRTUAL  │ 1920 x 1080 │ 23,24,25,26       │         │
│ Nexus6            │ Motorola           │ Nexus 6                             │ VIRTUAL  │ 2560 x 1440 │ 21,22,23,24,25    │         │
│ Nexus6P           │ Google             │ Nexus 6P                            │ VIRTUAL  │ 2560 x 1440 │ 23,24,25,26,27    │         │
│ Nexus7            │ Asus               │ Nexus 7 (2012)                      │ VIRTUAL  │ 1280 x 800  │ 19,21,22          │         │
│ Nexus7_clone_16_9 │ Generic            │ Nexus7 clone, DVD 16:9 aspect ratio │ VIRTUAL  │ 1280 x 720  │ 23,24,25,26       │ beta    │
│ Nexus9            │ HTC                │ Nexus 9                             │ VIRTUAL  │ 2048 x 1536 │ 21,22,23,24,25    │         │
│ NexusLowRes       │ Generic            │ Low-resolution MDPI phone           │ VIRTUAL  │  640 x 360  │ 23,24,25,26,27,28 │         │
│ OnePlus5          │ OnePlus            │ OnePlus 5                           │ PHYSICAL │ 1920 x 1080 │ 26                │         │
│ Pixel2            │ Google             │ Pixel 2                             │ VIRTUAL  │ 1920 x 1080 │ 26,27,28          │         │
│ a5y17lte          │ Samsung            │ Galaxy A5 2017                      │ PHYSICAL │ 1920 x 1080 │ 24                │         │
│ athene            │ Motorola           │ Moto G4 Plus                        │ PHYSICAL │ 1920 x 1080 │ 23                │         │
│ athene_f          │ Motorola           │ Moto G4                             │ PHYSICAL │ 1920 x 1080 │ 23                │         │
│ cheryl            │ Razer              │ Razer Phone                         │ PHYSICAL │ 2560 x 1440 │ 25                │         │
│ crownqlteue       │ Samsung            │ Galaxy Note 9 USA                   │ PHYSICAL │ 2220 x 1080 │ 27                │         │
│ flo               │ Asus               │ Nexus 7 (2013)                      │ PHYSICAL │ 1920 x 1200 │ 19,21             │         │
│ g3                │ LG                 │ LG G3                               │ PHYSICAL │ 2560 x 1440 │ 19                │         │
│ grandpplte        │ Samsung            │ Galaxy J2 Prime SM-G532M            │ PHYSICAL │  960 x 540  │ 23                │         │
│ griffin           │ Motorola           │ Moto Z XT1650                       │ PHYSICAL │ 2560 x 1440 │ 24                │         │
│ hammerhead        │ LG                 │ Nexus 5                             │ PHYSICAL │ 1920 x 1080 │ 21,23             │         │
│ harpia            │ Motorola           │ Moto G Play (4th Gen) XT1607        │ PHYSICAL │ 1280 x 720  │ 23                │         │
│ hero2lte          │ Samsung            │ Galaxy S7 edge                      │ PHYSICAL │ 1440 x 2560 │ 23                │         │
│ herolte           │ Samsung            │ Galaxy S7                           │ PHYSICAL │ 1440 x 2560 │ 23,24             │         │
│ hlte              │ Samsung            │ Galaxy Note 3 Duos                  │ PHYSICAL │ 1920 x 1080 │ 19                │         │
│ htc_m8            │ HTC                │ HTC One (M8)                        │ PHYSICAL │ 1920 x 1080 │ 19                │         │
│ hwALE-H           │ Huawei             │ Huawei P8 lite                      │ PHYSICAL │ 1280 x 720  │ 21                │         │
│ j1acevelte        │ Samsung            │ Galaxy J1 ace SM-J111M              │ PHYSICAL │  800 x 480  │ 22                │         │
│ j7xelte           │ Samsung            │ Galaxy J7 (SM-J710MN)               │ PHYSICAL │ 1280 x 720  │ 23                │         │
│ lt02wifi          │ Samsung            │ Galaxy Tab 3                        │ PHYSICAL │  600 x 1024 │ 19                │         │
│ lucye             │ LG                 │ LG G6 LGUS997                       │ PHYSICAL │ 2880 x 1440 │ 24                │         │
│ lv0               │ LG                 │ LG K3                               │ PHYSICAL │  854 x 480  │ 23                │         │
│ m0                │ Samsung            │ Samsung Galaxy S3                   │ PHYSICAL │ 1280 x 720  │ 18                │         │
│ mata              │ Essential Products │ Essential PH-1                      │ PHYSICAL │ 2560 x 1312 │ 25                │         │
│ mlv1              │ LG                 │ LG K4 (LG-X230)                     │ PHYSICAL │  854 x 480  │ 23                │         │
│ potter            │ Motorola           │ Moto G (5) Plus                     │ PHYSICAL │ 1920 x 1080 │ 24                │         │
│ sailfish          │ Google             │ Pixel                               │ PHYSICAL │ 1080 x 1920 │ 25,26,27,28       │         │
│ shamu             │ Motorola           │ Nexus 6                             │ PHYSICAL │ 2560 x 1440 │ 21,22,23          │         │
│ star2qlteue       │ Samsung            │ Samsung Galaxy S9+ (US)             │ PHYSICAL │ 2220 x 1080 │ 26                │         │
│ starqlteue        │ Samsung            │ Samsung Galaxy S9 (US)              │ PHYSICAL │ 2220 x 1080 │ 26                │         │
│ taimen            │ Google             │ Pixel 2 XL                          │ PHYSICAL │ 2880 x 1440 │ 26,27             │         │
│ victara           │ Motorola           │ Moto X                              │ PHYSICAL │ 1920 x 1080 │ 19                │         │
│ walleye           │ Google             │ Pixel 2                             │ PHYSICAL │ 1920 x 1080 │ 26,27,28          │ default │
│ zeroflte          │ Samsung            │ Galaxy S6                           │ PHYSICAL │ 2560 x 1440 │ 23                │         │
└───────────────────┴────────────────────┴─────────────────────────────────────┴──────────┴─────────────┴───────────────────┴─────────┘
```

or by run gcloud service

```gcloud firebase test android models list```
  
