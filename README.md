Samsung S9 | starlte | LineageOS 20 (Android 13)

Install TWRP Recovery (only need to do once)

https://dl.twrp.me/starlte/

twrp-3.7.0_9-0-starlte.img.tar | 40.7 MB | 2022-10-15

+ no-verity-opt-encrypt-6.1.zip

Boot into TWRP Recovery -> Wipe/Format -> Install

#1

https://lineage-archive.timschumi.net/ - probably not getting any more updates

lineage-20.0-20241229-nightly-starlte-signed.zip | 798 MB | 2024-12-29

#2

MindTheGapps-13.0.0-arm64 - probably not getting any more updates

https://github.com/MindTheGapps/13.0.0-arm64/releases/latest

MindTheGapps-13.0.0-arm64-20231025_200931.zip | 367 MB | 2023-10-25

or NikGapps-core-arm64 - probably not getting any more updates

https://sourceforge.net/projects/nikgapps/files/Releases/Android-13/

NikGapps-core-arm64-13-20260204-signed.zip | 106 MB | 2026-02-04

#3

https://github.com/topjohnwu/Magisk/releases

Magisk-v30.7.zip | 11.1 MB | 2026-02

Wipe Cache/Dalvik -> Reboot System -> Setup offline

Enable developer options

Stay awake = Enable

USB debugging = Enable

Advanced restart = Enable

Reboot -> Connect to Wi-Fi -> If Magisk doesn’t show to set up -> Install Magisk-v30.7.apk -> Open Magisk and setup, requires restart

From Magisk app -> Modules -> Install from storage PFLite -> Reboot

PFLite.MINIMAL.v2.0.P3XL.Android.13.zip

Now in Settings -> About it should say Model: Pixel 3 XL

Disable: Calculator, Calendar, Clock, Contacts, Gallery, Live Wallpaper Picker, Music, MusicFX, Recorder

Settings -> Display -> Screen timeout = 10min

Settings -> System -> Status bar -> Battery % = Next to the icon

Quick settings: Wi-Fi, Bluetooth | Quick Share, Battery Saver | Auto-Rotate, Airplane mode
