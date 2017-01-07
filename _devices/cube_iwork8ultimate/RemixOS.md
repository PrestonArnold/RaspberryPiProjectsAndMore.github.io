---
layout: rom
title: Remix OS 2.0 (Android 5.1.1)
subtitle: for Cube iWork8 Ultimate & iWork8 Air
date: 2016-07-15
tags: [cube_iwork8ultimate, RemixOS]
social-share: true
comments: true
---

This is my port of [Remix OS](http://www.jide.com/remixos) 2.0 for Cube iWork8 Ultimate (I1-T/I1-TD/I1-TWB/I1-TC) and iWork8 Air (I1-TF). This ROM is based on [Onda v820w CH](http://www.jide.com/remixos/devices/v820wch) official Remix OS release build B2016051301.

![screenshot]({{ site.url }}/devices/cube_iwork8ultimate/RemixOS/Screenshot_2016-07-15-17-47-01.png)

<span style="color:#FF0000;">Do not mirror my builds!</span> Please post a link to this page instead.

**RemixOS-20160715-cht_cr_mrd.zip**  
[https://www.androidfilehost.com/?fid=24659325368664682](https://www.androidfilehost.com/?fid=24659325368664682)  
md5:20c53bc58c41d948271ab2176377b2a6

**Working:**

- Wifi
- Audio (playback/input/routing/headphones/etc)
- Bluetooth
- Camera
- Hardware video decoding & encoding
- Hardware acceleration and OpenGL rendering
- Network/wifi location
- SD cards
- USB storage (MTP and PTP) & adb
- USB OTG (storage, mouse, keyboard)
- Touchscreen/multi-touch
- Sensors
- HDMI

**Not working:**

- ???

**Issues:**

- SELinux is in permissive mode
- It's still an early release - expect minor problems

**Thanks:**

- Jide for Remix OS

----
----

**15.7. changelog:**

- initial release

----
----

**How to install:**

1. boot into [TWRP recovery](/devices/cube_iwork8ultimate/TWRP)
2. backup -> backup (create a nandroid backup of your current ROM)
3. wipe -> advanced wipe -> wipe /system
4. wipe -> factory reset
5. install RemixOS-2016xxxx-cht_cr_mrd.zip
6. (install I1-TD/I1-TWB/I1-TF patch if necessary)
7. reboot system

**FAQ:**

Q: I don't have root. I don't have busybox. What should I do?  
*A: Download [SuperSU](http://download.chainfire.eu/supersu-stable) and/or [BusyBox](http://forum.xda-developers.com/attachment.php?attachmentid=3932008&d=1478780582) flashable zip and install it in TWRP.*

Q: I can't find developer options, why?  
*A: Settings -> About tablet -> Click 'Build number' several times*

Q: I have I1-TD/I1-TWB/I1-TC model with different touchscreen hardware. What should I do?  
*A: Download patch below suitable for your device and install it in TWRP.*

**RemixOS-cht_cr_mrd-I1-TD.zip**  
[https://www.androidfilehost.com/?fid=24659325368664685](https://www.androidfilehost.com/?fid=24659325368664685)  
md5:53d56202747439d5601184a1d4bf286b

**RemixOS-cht_cr_mrd-I1-TWB.zip**  
[https://www.androidfilehost.com/?fid=24659325368664683](https://www.androidfilehost.com/?fid=24659325368664683)  
md5:99de1beb3cabc14015588c2f598ad53a

**RemixOS-cht_cr_mrd-I1-TC.zip**  
[https://www.androidfilehost.com/?fid=24591000424954422](https://www.androidfilehost.com/?fid=24591000424954422)  
md5:db24d04310d9ccde30ac4dc33d2e5fa5

Q: I have iWork8 Air (I1-TF) with different display hardware. What should I do?  
*A: Download patch below and install it in TWRP.*

**RemixOS-cht_cr_mrd-I1-TF.zip**  
[https://www.androidfilehost.com/?fid=24659325368664684](https://www.androidfilehost.com/?fid=24659325368664684)  
md5:9a06ebc95b21f8ea86d6ce691f4e7adf

----
----