只用 Native-root-detector-v6.5.7.apk 和 Momo-v4.4.1.apk, 参考: https://gist.github.com/diyism/aa8a9c4b7423c2d31714029cb326e75f

# MagiskDetection
Collection of Some Publically Available POC Apps to Detect Root/Magisk presence. 

These applications have following detections:

APTest (me.garfieldhan.hiapatch) -
```sh
"Detect APatch" ( https://github.com/bmax121/APatch )
```

CrackME (com.kikyps.crackme) - 
Repo - https://github.com/kikyps/GarudaDefender
```sh
"Anti Hooking"
"Dynamic tamper detection (e.g Code Patching)"
"Anti FRIDA"
"Anti Stackplz"
"Anti Debugging & Breakpoint (Java & Native)"
"Anti Emulation"
"Root Detection"
"Certificate Signature Integrity"
"Emulator/Virtual Machine Detection"
"Game Engine Protection - Anti Cheat"
"Memory Patch Detection"
"Dalvik code patch detection"
"Screen Protection"
"Auto Clicker & Overlay attacks Detection"
"Fake GPS Detection"
"String Encryption (Java Layer Protection)"
"Control Flow Obfuscation (Java Layer Protection)"
"HTTP Capture Detection"
"Certificate SSL Pinning"
```

Detect Magisk(com.darvin.security) -
```sh
"Magisk Detection"
"Magisk Hide Detection"
```

DetectZ (com.test.detectz)

Source - https://github.com/apkunpacker/DetectZygisk
```sh
"Detect Zygisk forks - which are ptrace based"
"Detect - https://github.com/PerformanC/ReZygisk"
"Detect - https://github.com/Dr-TSNG/ZygiskNext"
"Detect - https://github.com/JingMatrix/NeoZygisk"
```

Hunter(com.zhenxi.hunter) -
```sh
"Apk Signature Verification"
"Magisk & Root Detection"
"Sandbox & Sandbox Detection"
"Frida & IDA Detection"
"libc Memory Detection"
"Unidbg Detection"
"Key function inlinehook & got table Detection"
"Anti-Debugging Detection"
"ISO strong Detection"
"Magisk Hide Detection"
"Custom ROM Detection"
```

Magisk Detector(io.github.vvb2060.magiskdetector) -
```sh
"Magisk Detection"
"Magisk Hide Detection"
```

MinotaurPoc(icu.nullptr.nativetest) -
```sh
"Magisk Detection"
"Zygisk Detection"
```

Momo(io.github.vvb2060.mahoshojo) -
```sh
"Frida Detection"
"Magisk Detection"
"Zygisk Detection"
"Magisk Modules Detection"
"Debugging Mode Detection"
"Developer Mode Detection"
"Bootloader Detection"
"System Files Modified By Magisk Detection"
"Package Manager abnormal Detection"
"Custom ROM Detection"
"SELinux State Detection"
``` 

NativeTest(icu.nullptr.nativetest) -
```sh
"Magisk Detection"
"Magisk Hide Detection"

Updated Version v30
https://play.google.com/store/apps/details?id=icu.nullptr.nativetest
"Detect Everything. Literally - Reverse it to find cutting edge detection ideas"
```

Oprek Detector(com.godevelopers.OprekCek) -
```sh
"Root Specific App Checks"
"Magisk Detection"
"Magisk Module Detection"
"SU Binary Detection"
"SELinux State Detection"
"Xposed Detection"
```

Rootbeer Sample(com.scottyab.rootbeer.sample) -
```sh
"Root Specific Apps Checks"
"SU Binary Check"
"Magisk Detection"
"Prop Detection"
"SELinux State Detection"
```

Ruru(com.byxiaorun.detector) -
```sh
"Root Specific Apps Check w/o Syscalls"
"Root Specific Apps Check with PackageManager"
"Xposed Hook Detection"
"Magisk Binary Detection"
"Zygisk Detection"
"Riru Detection"
"Prop Detection"
```

SafeCheck(com.ysh.hookapkverify) -
```sh
"Application Signature Detection"
"Magisk SU Detection"
"Syscall Hook Detection"
"Magisk Hide Detection"
"Zygisk Detection"
"Riru Detection"
```
Native Root Detector -
```sh
"Magisk Detection"
"Magisk SU Detection"
"Zygisk Detection"
"Zygisk-Assistant Detection"
"Possibly Denylist Detection"
"KernelSU Detection"
"APatch Detection"
"LSPosed Detection"
"Custom Rom Detection"
"Leaked Keybox Detection"
"Bootloader Detection"
"Root Management app installed detection"

Source - https://github.com/reveny/Android-Native-Root-Detector-Private
(You don't have access obviously)

```

Holmes -
```sh
"Detect Everything. Literally - Reverse it to find cutting edge detection ideas"
```

JingMatrix Demo
```sh
"Detect library injection in memory using maps/module counter"

Source - https://github.com/JingMatrix/Demo
and if main repo is deleted in any case then fork can be found at
https://github.com/apkunpacker/JingMatrixDemo
```


SHA256 of Each Files(Just to trace them back on VT/Koodous or somewhere else)

```sh
8a39869f0ace5a2e624f2392b0b15d813306d0589a43bed99090e9e0dbf2d086
52141ed109fb3e199d714deb99f0f794706de8420b180872c9801dbf247dbb80
a327f0ce5af72ee53cbd39d93c41d4c7ab8cd931ccd128c2d4cc89d41ee20b80
1ed654af2f99cf60c51e125d5a1ee3a9e3c7b37854c1f5862fcb49ecccff5ec9
f150900a62a651899cee8767adaf057ff83b3b383400eb198a9ae3cb698409a8
b4a3b33a3b3a9c423543bda59e0c9b1c5b74799da4c4ed272ff7971ecd3c8264
4605779cf733995d0a26cca54ab055d5cecbcf68fd710f5c7a4cb2e230826717
91da21e8a9103b283e0dba45e708af0ca94dd93eefe95740e87708937743e06d
3f027fbd5320f4def0271cf5425abe8a9081f655507236a1d4ceee8795d1f310
607ec962ba93cc9817129cb693ff0f335f500a297b5a297e71fbb998d0f6849c
066802ca09fe49ee9b62c4d94fd232886251d386baca010753d9975e201d3429
7844448585ee7357aba550c5cde03a3b5e9a247dc36c5fc79fa73905fb3a4ccf
6b6017ef1d2c8e48a805beddb9ffb844d2a6dfc0e16dfd073195cba410fd0128
972d7f538dd4f27644b84cb8fbb9b3f176320455e83b1c69b29c999f55dc3258
843f8360000daa6554ba0e83116bc90e2eb69f39c93c8254ab3c5fd78d15d369
5b2cb3b3203cb0cb4e59235fca7d728dfeaba1467e045699625671bc1ede4f67
```
