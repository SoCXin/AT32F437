# [ESP32-C6](https://github.com/SoCXin/ESP32-C6)

#### [Vendor](https://github.com/SoCXin/Vendor)：[Espressif](https://github.com/SoCXin/espressif)
#### [Core](https://github.com/SoCXin/RISC-V)：[RISC-V](https://github.com/SoCXin/RISC-V)
#### [Level](https://github.com/SoCXin/Level)：1.22DMIPS/MHz x 160MHz

## [芯片描述](https://github.com/SoCXin/ESP32-C6/wiki)

[ESP32-C6](https://github.com/SoCXin/ESP32-C6) SP32-C6 的 CPU、内存和安全性能与 ESP32-C3 相似，它搭载 RISC-V 32 位单核处理器，时钟频率高达 160 MHz，内置 400 KB SRAM，384 KB ROM，并支持多个外部 SPI、Dual SPI、Quad SPI、QPI flash。ESP32-C6 具有 22 个可编程 GPIO 管脚，支持 ADC、SPI、UART、I2C、I2S、RMT、TWAI 和 PWM。

独特之处在于提供了对 2.4 GHz Wi-Fi 6 协议 (802.11ax) 的支持，并向下兼容 802.11 b/g/n。为优化和提升物联网设备性能，ESP32-C6 支持 802.11ax 的仅 20 MHz 信道带宽工作模式，以及 802.11b/g/n 协议的 20/40 MHz 带宽。此外，802.11ax 还支持 Station 工作模式，为设备提供更高的传输速率和更低的功耗。Bluetooth 5 (LE) 可基于广播扩展 (Advertising Extensions) 和 Coded PHY 实现远距离通信。

ESP32-C6 支持基于 RSA-3072 算法的安全启动、基于AES-128-XTS 算法的 flash 加密、用于保护设备身份安全的数字签名和 HMAC 模块。

#### 关键特性

*   Wi-Fi 6
*   BLE 5


### [资源收录](https://github.com/SoCXin)

* [参考文档](docs/)
* [参考资源](src/)
* [参考工程](project/)

### [选型建议](https://github.com/SoCXin)

[ESP32-C6](https://github.com/SoCXin/ESP32-C6)沿用乐鑫成熟的物联网开发框架 ESP-IDF，并且使用RISC-V内核。

###  [探索芯世界 www.SoC.xin](http://www.SoC.Xin)
