# dell5557 

## 配置

硬件  | 型号
---  | :--
处理器 | 英特尔酷睿 i5-6200U
显卡 |Intel HD Graphics 520
硬盘  |	 闪迪至尊 1T 
内存  |	三星 8GB DDR3 1600MHz x 2
无线 + 蓝牙 | BCM94360Z4 无线网卡
显示器 | 内置（15.6 英寸 ）
键盘  |	内置
鼠标  |	罗技 M220

## 注意：

* 1.解锁CfgLock的可以直接安装，没有解锁的，请在 Kernel->Quirks 勾选 AppleXcpmCfgLock。

* 2.BCM94360Z4 无线网卡，该网卡尺寸比网卡卡槽两边多出2mm，老版本解决方式是切边框，后续小兵会推出小尺寸版可以放下，请多多关注 BCM94360Z4 无线网卡 最新动态。

* 3.Mac 10.15 用0.6.8的引导。 

* 4.独显并未驱动只是改了核显名字（好玩）。 

## BIOS设置：

* General->Boot Sequence->Boot List Optiong->UEFI
  
* General->Advanced Boot Options->Enable Legacy Option ROMs

* System Configuration->SATA Operation->AHCI

* Secure Boot->Secure Boot Enable->Disable

* Intel@ Software Guard Extensions->Intel@ SGX Enable->Disable

* Intel@ Software Guard Extensions->Enclave Memory Size->128MB



![截屏2021-04-10 14 43 22](https://user-images.githubusercontent.com/45564110/114261205-f0311b80-9a0b-11eb-8369-cd277fa743c9.png)
![截屏2021-08-26 下午7 22 00](https://user-images.githubusercontent.com/45564110/130954912-6635894e-9685-4cdd-8ea4-91d8d226ab9e.png)
![截屏2021-08-26 下午7 22 13](https://user-images.githubusercontent.com/45564110/130954947-7835b3c7-6f73-440c-8344-0b921ec68e06.png)
![截屏2021-08-26 下午7 22 18](https://user-images.githubusercontent.com/45564110/130954965-6035128a-f9e4-404f-951e-9f3bc29eec73.png)
![截屏2021-08-26 下午7 22 34](https://user-images.githubusercontent.com/45564110/130954980-ba331ca5-69c4-4422-876e-cfb9de30016a.png)
![截屏2021-08-26 下午7 22 37](https://user-images.githubusercontent.com/45564110/130954989-7e143ed8-f63f-4ae9-864a-5dafde29b599.png)
![截屏2021-08-26 下午7 22 56](https://user-images.githubusercontent.com/45564110/130954994-8b522dd5-48a8-403b-b225-94091690e503.png)
![截屏2021-04-10 14 45 20](https://user-images.githubusercontent.com/45564110/114261244-1b1b6f80-9a0c-11eb-9d0d-ad7ed3a6901f.png)
![截屏2021-08-26 下午7 21 41](https://user-images.githubusercontent.com/45564110/130955060-27574818-0768-468c-ac15-35d35ccd4364.png)
![截屏2021-08-26 下午7 21 30](https://user-images.githubusercontent.com/45564110/130955076-7c64dd02-2a82-4ed4-9c3a-18316590388d.png)
![截屏2021-08-26 下午7 21 15](https://user-images.githubusercontent.com/45564110/130955087-1ac091be-cf20-4e1d-b75f-50fda5a26b1f.png)

