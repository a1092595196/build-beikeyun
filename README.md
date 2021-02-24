# build-beikeyun

[![Build Status](https://travis-ci.com/qijianjun/build-beikeyun.svg?branch=master)](https://travis-ci.com/qijianjun/build-beikeyun)
[![release](https://img.shields.io/github/release/qijianjun/build-beikeyun.svg)](https://github.com/qijianjun/build-beikeyun/releases)

### update

Fork自[hanwckf/build-beikeyun: scripts for build beikeyun firmware](https://github.com/hanwckf/build-beikeyun)，原版本使用的内核为4.4，似乎内核bug导致不规律断网的问题（[armbian无规律断网 · Issue #7 · hanwckf/build-beikeyun](https://github.com/hanwckf/build-beikeyun/issues/7)），此处发布armbian的新版本，试图解决此问题。
此处使用rock64最新版本的armbian固件构建，使用了[\[2021-02-17\] 53+、53+O S905x3(含x2)、S922x、贝壳云、我家云、微加云等OP固件 - OPENWRT专版 - 恩山无线论坛 - Powered by Discuz!](https://www.right.com.cn/forum/thread-4076037-1-1.html)中提供的dtb文件，帖子称此dtb文件通过给CPU增压实现稳定运行，默认最高频率为1296MHZ。
armbian当前内核的最新版本为5.4。使用中有问题请提issue。

### scripts for build beikeyun firmware

- armbian
  - default root password: 1234
- LibreELEC
  - default root password: libreelec
- Lakka
  - default root password: root
- alpine
  - default root password: admin
- archlinuxarm
  - default root password: admin
  - run `pacman-key --init && pacman-key --populate archlinuxarm` to init keyring
