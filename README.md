# Some Experience or Solutions :smile: :sunny: 
- __怎么把动态盘变成基本盘？__   
网上搜了很多方法，现在用自己的经验总结一个比较靠谱的！网上下载`Disk Genius`，是一个用于管理磁盘的工具，下载地址很多，自己找。    
然后不想更了，后续再看，嘻嘻

- __2019.03.30 周六__    
今日份工作：解决GPS无法稳定传输的问题！（应该是解决了:expressionless:)  
GPS在传输的时候数据的长度在不断变化，保存数据的数组长度不够，导致传输给雷达的信息会少几个字节，应该是GPRMC的校验位（等会去验证一下），这样导致电脑串口总是中断。现在增加了数组的长度，终于解决了！:relaxed:(确定是校验位)[GPRMC数据解析](https://www.cnblogs.com/roger0212/p/4436744.html)。  
今日想法：要学的东西好多啊，什么时候能像汪总一样优秀啊！:kissing_heart:  
第一次用ipad写GitHub,感觉好奇怪啊
- __2019.04.01 周一__    
弄了个Terminator终端配合zsh，好高端的样子，浩哥推荐！  
具体配置可以网上百度，可参照[CSND](https://blog.csdn.net/xungjhj/article/details/69377812)。 
- __2019.09.18 周三__
好久没有更新github了，今天重新捡起来随便写一写  
昨天重新安装ubuntu踩了好几个坑  
1. 电脑没有办法上网，ifconfig只有本地回环，使用**lspci**命令查看可以看到当前网卡信息为Ethernet controller: Intel Corporation Device 15bc (rev 10)，找了好久都没有找到解决方法，最终还是靠浩哥给我找的方案解决了[CSDN](https://blog.csdn.net/champwang/article/details/85244990?tdsourcetag=s_pctim_aiomsg)。浩哥牛逼！
2. ubuntu设置分辨率。一开始电脑只有一个分辨率，用的常用的xrandr方法不行，最后修改的grub成功[CSDN](https://blog.csdn.net/xj626852095/article/details/47703565)。


