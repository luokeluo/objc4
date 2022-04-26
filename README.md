# 可调试的、基于M1芯片、macOS 12系统的objc4.

<!-- # **objc runtime**  -->
![build_status](https://github.com/0xxd0/objc4/workflows/build/badge.svg) 
[![Join the chat at https://gitter.im/0xxd0/objc4](https://badges.gitter.im/0xxd0/objc4.svg)](https://gitter.im/0xxd0/objc4?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) 
![support](https://img.shields.io/badge/support-macOS%20%7C%20iOS-orange.svg)

- [Version](#Version)
- [Installation](#Installation)
- [Usage](#Usage)
- [License](#license)


## **Version**

| macOS | macOS Version | Xcode Version | objc4 tarball version |
| - | - | - | - |
| <font color=Blue>macOS Monterey</font> | <font color=Blue>12.0.1</font> | <font color=Blue>13.2 (13C90)</font> | <font color=Blue>objc4-838</font> |

## **Installation**

Download zip or clone this repo, select **objc_debug** 、 **My Mac** and build.


## **Usage**

手动把编译产物`libobjc.A.dylib`加入到你的工程，或者直接在`objc_debug`的main文件打断点调试。
如果没有办法在main函数打断点，可以尝试写个类，提供一个方法，方法里面设置断点，在main函数里调用这个方法。


## License
This project is released under the **MIT License**. The objc4 project is released under the **APPLE PUBLIC SOURCE LICENSE Version 2.0**.
