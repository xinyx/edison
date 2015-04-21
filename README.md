# edison 参考资料

## get started:
  
https://software.intel.com/iot/getting-started

## 刷新固件:

* [常用刷新](https://communities.intel.com/docs/DOC-23200)
* [恢复固件|Building xFSTK on Ubuntu 14.04 (32-bit) for flashing Edison](https://communities.intel.com/message/257193#257193)  
		./flashall --recovery: 执行恢复过程
* 单个文件刷新
	当edison提示"GADGET DRIVER: usb_dnl_dfu"时, 用dfu-util刷新. 例如刷新u-boot-edison.bin:
		sudo dfu-util -v -d 8087:0a99 --alt u-boot0 -D u-boot-edison.bin

### wifi

http://www.intel.com/support/edison/sb/CS-035380.htm?wapkw=wifi+edison

## 编译内核

* http://www.ibm.com/developerworks/cn/linux/l-yocto-linux/
* http://www.arduino.cn/thread-10595-1-1.html
* http://www.arduino.cn/thread-12602-1-1.html

## 相关资料

* [IoT-Edison开发板开发者资源](https://software.intel.com/zh-cn/articles/intel-edison-developer-resources/?utm_campaign=CSDN&utm_source=intel.csdn.net&utm_medium=Link&utm_content=others-edison)
* [Edison开发模块资料](http://bbs.ickey.cn/group-topic-id-45783.html)
* [IntelEdisonDemoDay/documentation](https://github.com/IntelEdisonDemoDay/documentation)
* [intel Galileo Gen 2 and Intel Edison for Beginners](http://www.apress.com/apressopen/linux/9781484206904?gtmf=c)
* [boot Edison form SD card](https://communities.intel.com/message/282853)
* [Yocoto概念](http://guqian110.github.io/pages/2014/05/12/learning_yocto_from_zero_1_getting_started.html)
* [Yocoto Development Manual](http://www.yoctoproject.org/docs/1.8/dev-manual/dev-manual.html#dev-modifying-source-code)
* [Yocoto Linux Kernel Development Manual](http://www.yoctoproject.org/docs/latest/kernel-dev/kernel-dev.html)
* [Yocoto BSP Development Manual](http://www.yoctoproject.org/docs/1.8/bsp-guide/bsp-guide.html#using-the-yocto-projects-bsp-tools)
* [Yocoto Source Repositoris](http://git.yoctoproject.org/cgit.cgi)
* [Yocoto BSP User Guide](http://www.intel.com/support/edison/sb/CS-035278.htm)
