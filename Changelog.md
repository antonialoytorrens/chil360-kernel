 
Chil360 Kernel
==============

The Chil360 Kernel is an Android kernel for the following devices:
* Huawei Ascend Y300 (U8833)
* Huawei G510 (U8951)
* Huawei G330 (U8825)

It is based on the [huawei-kernel-3.4] by Dazzozo

Changelog
---------
v0.23
* Add FRandom
* BFQ I/O scheduler 7r2
* V(R) I/O scheduler
* FIOPS I/O scheduler
* ZEN I/O scheduler

v0.22
* Simple I/O scheduler (default)
* Dynamic FSync

v0.21
* Lowered swappiness 60->45
* Add optimized AES and SHA1 routines
* Add glibc memcopy and string
* Disabled Gentle Fair Sleepers for better UI performance 

v0.20
* Patch kernel from 3.4.0 to 3.4.82

v0.10
* Set optimization level by config
* Build Fixes to compile with -O3 & -Ofast
* Build fixes to compile with Linaro 4.7
* Build fixes to compile with Linaro 4.8

[huawei-kernel-3.4]:https://github.com/Dazzozo/huawei-kernel-3.4