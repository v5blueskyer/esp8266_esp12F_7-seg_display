# esp8266_esp12F_7-seg_display

简单的esp8266数码管时钟

简介：基于泽耀的8266的数码管时钟

原理图及pcb见：https://oshwhub.com/blueskyer/shi-yao-ke-ji-di8266-di12f-ji-lie-ji-chu-wai-wei-dian-lu
 QQ技术群：801516857


20211222更新，增加了3d外壳。

由于黑色透光性太差就挖孔了，如果使用白色材料打印就没必要挖直接数码管贴合前面板1mm位置效果会很好，前后面板靠胶水固定或者橡皮筋，如果铜柱不够可以加几个空白板子垫上。

 

20211019更新，应群友需要，增加了常规型esp8266（esp12F）的原理图和pcb图

 

偶然间得到一个和8266差不多的芯片，但是引脚封装又不同，就单独画个板子了。

 

打板直接使用附件的Gerber_PCBXXX里面的

 

因为pcb立创导入会自动重新铺铜会出问题，主要是8266天线区，我是先开槽然后自动布线和铺铜的再去掉开槽区。如果重新铺铜会把天线区也铺设铜，需要自行重新修改一下再生成Gerber文件。

 

数码管用8位数码管max7219系列，程序文件夹"ESP8266_Network_Clock_7SEGMAX7219"

 

不想做时钟当做开发板使用，焊接2个8p排针即可。

 

泽耀科技的板子没加ch340之类的电路，需要接usb转ttl手动下载（接上usb转ttl后，同时按住rst和flash按键，再松开rst，接着松开flash按键即可进入下载模式）。（已验证可正常使用）

 

常规型esp8266的加了ch340电路，可以typec直接下载。（未验证，希望有打板的评论区回复一下）

 
