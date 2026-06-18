# Dirac Audio Nothing Phone 1 Magisk Module

## DISCLAIMER
- Nothing apps and blobs are owned by Nothing™.
- Dirac apps and blobs are owned by Dirac™.
- The MIT license specified here is for the Magisk Module only, not for Nothing & Dirac apps and blobs.

## Descriptions
- Equalizer sound effect ported from Nothing Phone 1 (Spacewar) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Global type sound effect

## Sources
- https://dumps.tadiphone.dev/dumps/nothing/spacewar qssi-user-14-UP1A.231005.007-2406122149-release-keys
- /system/vendor/lib64: https://dumps.tadiphone.dev/dumps/nothing/pong qssi-user-14-UP1A.231005.007-2410161700-release-keys
- libmagiskpolicy.so: Magisk (stable) 30.7 (30700)

## Changelog

v1.6
- DiracDMPUI.apk v1.5:
  - Target SDK 35
  - Change package name to reiryuki.diracdmpui
  - Change icon
  - Add launch animation
- Support NoMount metamodule
- Update libmagiskpolicy.so from Magisk (stable) 30.7 (30700)
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/

v1.5
- Does not disable raw playback (You can use Audio Compatibility Patch Reborn Magisk Module instead)

v1.4
- Fix wrong target in latest KernelSU

v1.3
- Fix crashes

v1.2
- Tidy up aml.sh
- Exclude \*audio\*effects\*haptic\*.xml
- Fix wrong file permissions in some ROMs

v1.1
- Fix selinux denials
- Abort installation if fail to mount mirror system

v1.0
- Fix SDK detections in NothingDiracService_DMP.apk
- Fix BLUETOOTH_CONNECT permission
- Improve /odm and /my_product support detection

v0.9
- Detects settings secure audio_effect_enable and dirac_mode state on boot

v0.8
- Fix state detection on boot
- Revert targetSDK to 34 and fix the crashes
- Remove android.intent.action.USER_PRESENT receiver
- Apply sound effect to patch and rerouting stream by default
- Add new optional dirac.game

v0.7
- Fix a crash in SDK 32 and bellow
- DiracDMPUI.apk v1.4
- Fix receiver android.intent.action.USER_PRESENT not allowed in background

## Screenshots
https://t.me/ryukimodsscreenshots/41

## Requirements
- armeabi-v7a or arm64-v8a architecture
- Android 9 (SDK 28) and up
- HIDL audio service
- Magisk or Kitsune Mask or KernelSU or Apatch installed

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs or https://github.com/KernelSU-Modules-Repo/magic_mount_rs or https://github.com/KernelSU-Modules-Repo/hybrid_mount or https://github.com/maxsteeel/nomount first depending on ROM compatibility
- Install this module https://devuploads.com/vkdcxhm9qiqs via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Install AML Magisk Module https://t.me/ryukinotes/34 only if using any other else audio mod module
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot afterwards

## Optionals
- https://t.me/ryukinotes/80
- Global: https://t.me/ryukinotes/35
- Stream: https://t.me/ryukinotes/52

## Troubleshootings
Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- @HuskyDG
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


