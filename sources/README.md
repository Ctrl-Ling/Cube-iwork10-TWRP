# 文件说明

recovery_flash_tool.zip为twrp刷入工具，默认刷入我移植的twrp3.0

本文件夹下还有另外三个文件，分别是官方原厂rec，我移植的twrp3.0，网友移植的twrp2.9

功能：本recovery移植自台电。所以显示的也是台电，不影响使用。
bootrecovery.bat  用于启动recovery
flashrecovery.bat用于将recovery刷入平板
在电脑使用时请安装intel.driver下的三个驱动，以免选成刷机失败
使用前请先将平板完全关机，再按 音量上+音量下+电源键开机，确认平板进入qnx模式。接上数据线，点击flashrecovery.bat即可刷入rec

进入REC方法 
完全关机平板，开机选择安卓点OK，马上长按音量减直到进入fastboot
音量键选择recovery mode 电源键确认即可进入rec

其余操作请自行百度

另外，本rom针对iwork10。其它类似的机器，如obook10 x98 plus也许也可以修改使用

默认是刷入@Ctrl制作的twrp3.0(recovery.img)，如果想刷入twrp2.9的重命名recovery2.9.img替换recovery.img即可

本刷入rec功能由windxixi提供
注：刷入rec的同时会解锁平板BL，并且会清除安卓的数据以及安卓SD卡文件，注意备份
