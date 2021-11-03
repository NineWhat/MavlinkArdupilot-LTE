# MavlinkArdupilot-LTE
  
[4G图传控制一体电台](#4G图传控制一体电台)
  
CPU：NXP MCIMX6G2CVM05AA (MYS-6ULX-IND)  
  
System：Linux  imx_4.1.15_2.0.0_ga  
  
4G Moduler：QUECTEL EC20CEFRG-MINIPCIE-C  
  
Camera: OV2659(MY-CAM011B 1632*1212 8-BIT 222mW)  
  
Server：Tencent Cloud  

Development Environment：Ubuntu 16.04 64bit distribution  
  
## 安装软件包
	```
	sudo apt-get install build-essential git-core libncurses5-dev \
	flex bison texinfo zip unzip zlib1g-dev gettext u-boot-tools \
	g++ xz-utils mtd-utils gawk diffstat gcc-multilib python git \
	make gcc g++ diffstat bzip2 gawk chrpath wget cpio texinfo lzop
	```

## 随笔
  2021/09/28 编译UBOOT  
  2021/11/03 修改LINUX内核，驱动EC20  
