# Lenovo-M710q-QNCT-Hackintosh
EFI for Lenovo-M710q-QNVH with OpenCore 0.8.8 bootloader   

<img width="586" alt="image" src="https://user-images.githubusercontent.com/8513521/218945577-c0f74733-4e0c-4306-a124-01fec6905af3.png">
<img width="650" alt="image" src="https://user-images.githubusercontent.com/8513521/218945873-1aee484c-d23b-425e-8363-1053e7585db7.png">


### Computer Spec:

| Component        | Specifications                         |
| ---------------- | ---------------------------------------|
| CPU              | Intel® Core™ i7-8850H(ES) (QNVH)       |
| iGPU             | Intel® UHD Graphics 630                |
| RAM              | 2 * 16GB DDR4 2666Mhz                   |
| NVMe             | Kioxia RC10 1T      |
| LAN              | Intel I219-V                           |
| Audio            | Realtek ALC294                         |
| WiFi & Bluetooth | Intel Wi-Fi 6 AX200 / 7265AC           |
| SMBIOS           | MacMini8,1                             |
| BootLoader       | OpenCore 0.8.8                         |

### What Works:

- [x] Intel Intel® UHD Graphics 630 iGPU DP Output
- [x] ALC294 Internal Speakers
- [x] ALC294 & DP Audio Output
- [x] ALC294 Audio Input
- [x] All USB Ports
- [x] Intel I219-V
- [x] Intel Wi-Fi & Bluetooth
- [x] NVRAM

### BIOS Settings:

* Update BIOS to M1AKT51A, DVMT to 128M
* Enable:

* Disable:  
CSM

####  
更新BIOS到最新并魔改,推荐指定频率上限如: 六核3.0G , 然后指定显卡频率上限 推荐800MHz左右, 风扇安静 

在BIOS中必须完全关闭CSM，使用UEFI引导,设置DVMT为64M以上
然后重启安装macOS     

 
