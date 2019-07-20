# MYNT® EYE D SDK

[![](https://img.shields.io/badge/MYNT%20EYE%20D%20SDK-v1.7.9-brightgreen.svg?style=flat)](https://github.com/slightech/MYNT-EYE-D-SDK)


MYNT® EYE D SDK is a library for MYNT® EYE Depth cameras.

## Support platforms

* Linux x64 & aarch64
  * Tested on PC and TX2, with Ubuntu 16.04 (GCC 5).
* Windows x64
  * Tested on PC with Windows 10 and Visual Studio 2017.

## Documentations

API reference and the guide documentations.

* en: [![](https://img.shields.io/badge/Download-PDF-blue.svg?style=flat)](https://readthedocs.org/projects/mynt-eye-d-sdk/downloads/pdf/latest/) [![](https://img.shields.io/badge/Download-HTML-blue.svg?style=flat)](https://readthedocs.org/projects/mynt-eye-d-sdk/downloads/htmlzip/latest/) [![](https://img.shields.io/badge/Online-HTML-blue.svg?style=flat)](http://mynt-eye-d-sdk.rtfd.io/)
* zh-Hans: [![](https://img.shields.io/badge/Download-PDF-blue.svg?style=flat)](https://readthedocs.org/projects/mynt-eye-d-sdk-docs-zh-cn/downloads/pdf/latest/) [![](https://img.shields.io/badge/Download-HTML-blue.svg?style=flat)](https://readthedocs.org/projects/mynt-eye-d-sdk-docs-zh-cn/downloads/htmlzip/latest/) [![](https://img.shields.io/badge/Online-HTML-blue.svg?style=flat)](https://mynt-eye-d-sdk.rtfd.io/zh_CN/latest/)

### Quick Start Guide

* en:
  * [Ubuntu Source Installation](https://mynt-eye-d-sdk.rtfd.io/en/latest/sdk/install_ubuntu_src.html)
  * [Windows Source Installation](https://mynt-eye-d-sdk.rtfd.io/en/latest/sdk/install_win_src.html)
    * [Windows EXE Installation](https://mynt-eye-d-sdk.rtfd.io/en/latest/sdk/install_win_exe.html)
* zh-Hans:
  * [Ubuntu 源码安装](https://mynt-eye-d-sdk.rtfd.io/zh_CN/latest/sdk/install_ubuntu_src.html)
  * [Windows 源码安装](https://mynt-eye-d-sdk.rtfd.io/zh_CN/latest/sdk/install_win_src.html)
    * [Windows EXE 安装](https://mynt-eye-d-sdk.rtfd.io/zh_CN/latest/sdk/install_win_exe.html)
    
### Ubuntu 14.04 with kernel 4.19 installation

```
wget -q -O libstdc++6 http://security.ubuntu.com/ubuntu/pool/main/g/gcc-5/libstdc++6_5.4.0-6ubuntu1~16.04.10_amd64.deb
sudo dpkg --force-all -i libstdc++6
printf '\x02' | dd of=libeSPDI.so.3.0.24.05 bs=1 seek=145474 count=1 conv=notrunc
```

## Mirrors

国内镜像：[码云](https://gitee.com/mynt/MYNT-EYE-D-SDK)。

## License

This project is licensed under the [Apache License, Version 2.0](/LICENSE). Copyright 2018 Slightech Co., Ltd.
