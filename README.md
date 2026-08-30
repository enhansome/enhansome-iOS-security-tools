# awesome iOS security tools with stars

> List of all interesting iOS tools for security purpose

### Helpful Tools

* [ish](https://github.com/ish-app/ish) ⭐ 20,380 | 🐛 704 | 🌐 C | 📅 2026-08-22. A project to get a Linux shell running on iOS, using usermode x86 emulation and syscall translation.

* [ipatool](https://github.com/majd/ipatool) ⭐ 10,004 | 🐛 21 | 🌐 Go | 📅 2026-08-29

* [idb-facebook](https://github.com/facebook/idb/) ⭐ 5,302 | 🐛 182 | 🌐 Swift | 📅 2026-08-28. Tool for replacing WebDriverAgent.

* [WebDriverAgent](https://github.com/facebookarchive/WebDriverAgent) ⚠️ Archived. Archive.

* [frida-ios-dump](https://github.com/AloneMonkey/frida-ios-dump) ⭐ 3,922 | 🐛 107 | 🌐 JavaScript | 📅 2023-05-03 Pull a decrypted IPA from a jailbroken device

* [Clutch](https://github.com/KJCracks/Clutch) ⭐ 3,824 | 🐛 43 | 🌐 Objective-C | 📅 2024-11-15. Clutch is a high-speed iOS decryption tool. Clutch supports the iPhone, iPod Touch, and iPad as well as all iOS version, architecture types, and most binaries. Clutch is meant only for educational purposes and security research.

* [bagbak](https://github.com/ChiChou/bagbak) ⭐ 1,497 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-24. Yet another frida based iOS dumpdecrypted. Also decrypts app extensions

* [Keychain-Dumper](https://github.com/ptoomey3/Keychain-Dumper) ⭐ 1,419 | 🐛 19 | 🌐 Objective-C | 📅 2024-08-15

* [idb](https://github.com/dmayer/idb) ⭐ 955 | 🐛 36 | 🌐 Ruby | 📅 2023-03-25

* [ipainstaller](https://github.com/autopear/ipainstaller) ⭐ 261 | 🐛 12 | 🌐 C | 📅 2018-07-03. The IPA can also be directly installed on the iOS device via the command line with ipainstaller

* [imobax](https://github.com/Siguza/imobax) ⭐ 202 | 🐛 2 | 🌐 C | 📅 2022-05-28. The iOS Mobile Backup Xtractor.

* [itms-services](https://www.npmjs.com/package/itms-services) Getting the IPA File from an OTA Distribution Link

  ```shell
  npm install -g itms-services
  itms-services -u "itms-services://?action=download-manifest&url=https://s3-ap-southeast-1.amazonaws.com/test-uat/manifest.plist" -o - > out.ipa
  ```

* [checkra1n](https://github.com/checkra1n)

* [unc0ver.dev](https://unc0ver.dev/)

* [plistutil](https://manpages.debian.org/experimental/libplist-utils/plistutil.1.en.html)

  ```shell
  apt install libplist-utils
  plistutil -i Info.plist -o Info_xml.plist
  ```

### [libimobiledevice](https://libimobiledevice.org/)

* [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) ⭐ 8,152 | 🐛 848 | 🌐 C | 📅 2026-06-10 A library to communicate with services on iOS devices using native protocols.

* [ios-app-signer](https://github.com/DanTheMan827/ios-app-signer) ⭐ 6,313 | 🐛 123 | 🌐 Objective-C | 📅 2025-09-01 This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device.

* [ipsw](https://github.com/blacktop/ipsw) ⭐ 3,675 | 🐛 7 | 🌐 Go | 📅 2026-08-28. iOS/macOS Research Swiss Army Knife

* [idevicerestore](https://github.com/libimobiledevice/idevicerestore) ⭐ 1,920 | 🐛 332 | 🌐 C | 📅 2026-08-23 A command-line application to restore firmware files to iOS devices.

* [usbmuxd](https://github.com/libimobiledevice/usbmuxd) ⭐ 1,754 | 🐛 117 | 🌐 C | 📅 2025-12-06 A socket daemon to multiplex connections from and to iOS devices.

* [ideviceinstaller](https://github.com/libimobiledevice/ideviceinstaller) ⭐ 1,447 | 🐛 67 | 🌐 C | 📅 2025-10-30 A command-line application to manage apps and app archives on iOS devices.

* [ifuse](https://github.com/libimobiledevice/ifuse) ⭐ 1,016 | 🐛 61 | 🌐 C | 📅 2026-04-22 A fuse filesystem implementation to access the contents of iOS devices.

* [libusbmuxd](https://github.com/libimobiledevice/libusbmuxd) ⭐ 687 | 🐛 31 | 🌐 C | 📅 2025-09-07 A client library for applications to handle usbmux protocol connections with iOS devices.

* [libirecovery](https://github.com/libimobiledevice/libirecovery) ⭐ 651 | 🐛 47 | 🌐 C | 📅 2026-08-23 The libirecovery library allows communication with iBoot/iBSS of iOS devices via USB.

* [libplist](https://github.com/libimobiledevice/libplist) ⭐ 635 | 🐛 32 | 🌐 C | 📅 2026-05-22 A small portable C library to handle Apple Property List files in binary or XML format.

* [libideviceactivation](https://github.com/libimobiledevice/libideviceactivation) ⭐ 362 | 🐛 19 | 🌐 C | 📅 2025-09-07 A library to manage the activation process of Apple iOS devices.

* [ldid2](https://github.com/xerub/ldid) ⭐ 116 | 🐛 2 | 🌐 C++ | 📅 2020-11-29

* Requirements

  ```shell
  sudo apt-get install \
  build-essential \
  checkinstall \
  git \
  autoconf \
  automake \
  libtool-bin \
     libzip-dev \
     libxml2-dev \
  libcurl4-openssl-dev \
     zlib1g-dev \
     libfuse-dev \
  libreadline-dev \
  libusb-1.0-0-dev \
  ```

  ```shell
  sudo apt-get install \
  doxygen \
  cython
  ```

* All modules are installed with the  following commands (in the following order)

  ```shell
  ./autogen.sh
  make
  sudo make install
  sudo ldconfig 
  ```

### nowsecure tools

* [r2frida](https://github.com/nowsecure/r2frida) ⭐ 1,435 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-24 Radare2 and Frida better together.

* [node-applesing](https://github.com/nowsecure/node-applesign) ⭐ 483 | 🐛 27 | 🌐 TypeScript | 📅 2026-07-02 NodeJS module and commandline utility for re-signing iOS applications (IPA files).

* [ipa-extract-info](https://github.com/nowsecure/ipa-extract-info) ⭐ 41 | 🐛 5 | 🌐 JavaScript | 📅 2023-03-04 Extract the Info.plist from an IPA, in node.js and the browser!

### ioscontrol

* [ios-deploy](https://github.com/ios-control/ios-deploy) ⭐ 3,637 | 🐛 45 | 🌐 Objective-C | 📅 2024-06-24 Install and debug iOS apps from the command line. Designed to work on un-jailbroken devices (Requirement - MacOs)

## Static Analysis

* [jtool.ELF64](https://github.com/MobSF/Mobile-Security-Framework-MobSF/blob/master/mobsf/StaticAnalyzer/tools/ios/jtool.ELF64) ⭐ 21,664 | 🐛 25 | 🌐 JavaScript | 📅 2026-08-27
* [apfs-fuse](https://github.com/sgan81/apfs-fuse) ⭐ 2,137 | 🐛 125 | 🌐 C++ | 📅 2024-08-13
* [Mara Framework](https://github.com/xtiankisutsa/MARA_Framework) ⭐ 670 | 🐛 3 | 🌐 Python | 📅 2019-07-26
* [DyldExtractor](https://github.com/arandomdev/DyldExtractor) ⚠️ Archived
* [Ghidra](https://ghidra-sre.org/)
  * [Ghidra-script](https://github.com/ghidraninja/ghidra_scripts) ⭐ 1,166 | 🐛 13 | 🌐 YARA | 📅 2020-10-07
* [Cutter](https://cutter.re/)
* [Radare2](https://rada.re/n/)
* Hooper
* [ipa-extract-info](https://www.npmjs.com/package/ipa-extract-info)
* [jtool2](https://newosxbook.com/tools/jtool.html)
* [disarm](https://newosxbook.com/tools/disarm.html)

## Dynamic Analysis

* [objection](https://github.com/sensepost/objection) ⭐ 9,351 | 🐛 55 | 🌐 Python | 📅 2026-07-23 objection is a runtime mobile exploration toolkit, powered by Frida, built to help you assess the security posture of your mobile applications, without needing a jailbreak.

* [reFlutter](https://github.com/Impact-I/reFlutter) ⭐ 2,738 | 🐛 11 | 🌐 Python | 📅 2026-08-11. reFlutter.

* [appmon](https://github.com/dpnishant/appmon) ⚠️ Archived. AppMon is an automated framework for monitoring and tampering system API calls of native macOS, iOS and android apps. It is based on Frida. [Documentation](https://dpnishant.github.io/appmon/).

* [Grapefruit](https://github.com/ChiChou/grapefruit) ⭐ 1,379 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-11 Grapefruit: Runtime Application Instruments for iOS.

* [frida-ios-hook](https://github.com/noobpk/frida-ios-hook) ⭐ 1,184 | 🐛 4 | 🌐 JavaScript | 📅 2026-05-05. A script that helps you trace classes, functions, and modify the return values of methods on iOS platform.

* [frida-ios-hook](https://github.com/noobpk/frida-ios-hook) ⭐ 1,184 | 🐛 4 | 🌐 JavaScript | 📅 2026-05-05. A tool that helps you easy trace classes, functions, and modify the return values of methods on iOS platform.

* [fridump](https://github.com/Nightbringer21/fridump) ⭐ 859 | 🐛 27 | 🌐 Python | 📅 2024-08-07. A universal memory dumper using Frida.

* [introspy-iOS](https://github.com/iSECPartners/Introspy-iOS) ⭐ 739 | 🐛 20 | 🌐 Objective-C | 📅 2016-10-26 Blackbox tool to help understand what an iOS application is doing at runtime and assist in the identification of potential security issues.

* [iOS-Tagent](https://github.com/AirtestProject/iOS-Tagent) ⭐ 722 | 🐛 147 | 🌐 Objective-C | 📅 2025-12-03. iOS-Tagent is a project based on facebook WebDriverAgent and intend to fit Airtest Project.

* [iOS-Debug-Hacks](https://github.com/aozhimin/iOS-Debug-Hacks) ⭐ 681 | 🐛 1 | 📅 2017-09-29

* [Fastbot\_iOS](https://github.com/bytedance/Fastbot_iOS) ⚠️ Archived Fastbot is a model-based testing tool for modeling GUI transitions to discover app stability problems. It combines machine learning and reinforcement learning techniques to assist discovery in a more intelligent way.

* [Frida-Mobile-Scripts](https://github.com/m0bilesecurity/Frida-Mobile-Scripts) ⭐ 435 | 🐛 0 | 🌐 JavaScript | 📅 2021-08-10 Collection of useful FRIDA Mobile Scripts

* [Frida-Script-Runner](https://github.com/z3n70/Frida-Script-Runner) ⭐ 374 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-15. Frida Script Runner v1.3 is a versatile web-based tool designed for Android and iOS penetration testing purposes.

* [rvi\_capture](https://github.com/gh2o/rvi_capture) ⭐ 216 | 🐛 2 | 🌐 Python | 📅 2024-03-26. rvictl for Linux and Windows: capture packets sent/received by iOS devices. A utility to create packet capture dumps from iOS devices; useful for debugging network activity via Wireshark.

* [Fridax](https://github.com/NorthwaveSecurity/fridax) ⭐ 180 | 🐛 9 | 🌐 JavaScript | 📅 2023-04-04. Fridax enables you to read variables and intercept/hook functions in Xamarin/Mono JIT and AOT compiled iOS/Android applications.

* [iOS Developer Image](https://cgithub.com/haikieu/xcode-developer-disk-image-all-platforms/tree/master/DiskImages/iPhoneOS.platform/DeviceSupport).

### nowsecure

* [fsmon](https://github.com/nowsecure/fsmon) ⭐ 1,024 | 🐛 21 | 🌐 C | 📅 2026-04-11 FileSystem Monitor utility that runs on Linux, Android, iOS and OSX.
* [frida-cycript](https://github.com/nowsecure/frida-cycript) ⭐ 397 | 🐛 13 | 🌐 C | 📅 2023-03-04 This is a fork of \[Cycript] 1 in which we replaced its runtime with a brand new runtime called \[Mjølner] 3 powered by \[Frida] 4. This enables frida-cycript to run on all the platforms and architectures maintained by \[frida-core] 8.
* [frida-trace](https://github.com/nowsecure/frida-trace) ⭐ 238 | 🐛 20 | 🌐 JavaScript | 📅 2025-06-16 Trace APIs declaratively through Frida.
* [frida-screenshot](https://github.com/nowsecure/frida-screenshot) ⭐ 52 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-18 Grab screenshots using Frida.

### Framework

* [MobSf](https://github.com/MobSF/Mobile-Security-Framework-MobSF) ⭐ 21,664 | 🐛 25 | 🌐 JavaScript | 📅 2026-08-27
* [RMS-Runtime-Mobile-Security](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security) ⭐ 3,076 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-03
* [Medusa](https://github.com/Ch0pin/medusa) ⭐ 2,334 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-11. Binary instrumentation framework based on FRIDA
* [pirogue](https://pts-project.org/). Mobile device forensics & digital investigation.

***

## Jailbreak

* \[checkra1n]
* \[palera1n]
* [AppSync](https://cydia.akemi.ai/?page/net.angelxwind.appsyncunified). AppSync is a tweak that patches installd, allowing the installation of fake-signed IPA packages
* [Cydia Impactor](http://www.cydiaimpactor.com/). This tool was originally created to
  jailbreak iPhones, but has been rewritten to sign and install IPA packages to iOS devices via sideloading.

***

## Resources and Tutorial

* [RE-iOS-Apps](https://github.com/ivRodriguezCA/RE-iOS-Apps) ⭐ 2,901 | 🐛 2 | 📅 2024-04-17
* [iOS-Reverse-Engineering](https://github.com/GhidraEnjoyr/iOS-Reverse-Engineering) ⭐ 275 | 🐛 0 | 📅 2024-08-01
* [ios-frida-objection-cheat-sheet](https://www.virtuesecurity.com/kb/ios-frida-objection-pentesting-cheat-sheet/)
* [ios-Swift Anti-Jailbreak Bypass with Frida](https://syrion.me/blog/ios-swift-antijailbreak-bypass-frida/)
* [iOS-Bypass-Jailbreak](https://philkeeble.com/ios/reverse-engineering/iOS-Bypass-Jailbreak/)
* [Post-on-iOS-RE](https://philkeeble.com/categories/#ios)

***

## iOS Forenscics

* [ios\_forensics\_suite](https://github.com/piotrbania/ios_forensics_suite) ⭐ 68 | 🐛 0 | 🌐 HTML | 📅 2024-10-25

***

## CTF with iOS app

* [awesome-mobile-ctf](https://github.com/xtiankisutsa/awesome-mobile-CTF) ⭐ 1,165 | 🐛 2 | 📅 2022-06-26
* [NCC-CON-2018](https://ch1kpee.com/2018/01/08/ncc-con-2018-ios-ctf-solutions/)
* [ios-ctf](https://www.ivrodriguez.com/mobile-ctf/)
* [Walkthrough of an iOS CTF](https://www.optiv.com/explore-optiv-insights/source-zero/walkthrough-ios-ctf)
* [H1702 CTF](http://redgetan.cc/h1_702-ctf-reversing-ios-android-arm-writeup/)
* [frida-ios-jailbreak-bypass](https://syrion.me/blog/ios-swift-antijailbreak-bypass-frida/)
* [bypass-jailbreak-detection-ios](https://blog.attify.com/bypass-jailbreak-detection-frida-ios-applications/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
