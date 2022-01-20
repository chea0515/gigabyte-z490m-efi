# Gigabyte Z490M Gaming X黑苹果efi分享
## 配置
```java
#主板:	Gigabyte Z490M Gaming X	 
#内存:	威刚万紫千红DDR4 2666 16G x 2
#cpu: Core i5-10400	 
#硬盘:	西部数据SN550 500G
#机箱:	乔思伯V4	 
#网卡:	bcm94360cs白果拆机卡三天线
#电源:	先马实力先锋600W	 
#显示器: 优派28英寸4K显示器VX2831-4K-HD
#散热风扇: 大水牛BF80 8CM x 2
```
 
## 注意事项
1. 两条16G内存条，插2/4两个插槽；
2. 已修改 SSDT，所以如果要用此EFI，请按照这个配置来组装，特别是 主板、cpu、硬盘；
3. 已映射USB端口，网卡蓝牙连接线请插入F_USB2口（已映射为内置），不然会引起睡眠秒醒问题;
4. 已更换三码，也可以自已重新填入;
5. opencore版本为 OpenCore-0.7.5-RELEASE;
6. 固态硬盘可更换为西部数据SN750 1T；
7. 网卡可从某宝购买白果拆机卡,也可选用奋威T919；
8. 显示器输出插DP口；

## 功能测试（未发现不正常的功能，基本完美）
```java
#蓝牙： 正常
#wifi： 正常
#随航： 正常
#睡眠： 正常
#声音： 正常
#核显： 正常
```
