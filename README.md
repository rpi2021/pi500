# Pi3B相关，500G硬盘
## 基本想法
基础、安装自带方式，大全，有UI，常开；ssh/vnc等方式   
有音箱【WM8960 Audio HAT】

硬盘500G：4主分区    
300m  引导  
300G  根rpi  
100G  挂fat32     ?  /samba  
100G  ？？   终端?   32 ui 媒体中心  tf卡？  

固定IP  1.51   
无线网卡 启用ap  32.1 自发现  

pi300  
key登录  
2020-08-20-raspios-buster-arm64.zip  

### ip ap  
git clone https://github.com/oblique/create_ap.git   

### 硬盘，硬件  
硬盘引导处理  
挂分区  
samba 目录  
aria2 下载  


### 音  
git clone https://github.com/waveshare/WM8960-Audio-HAT  

蓝牙音箱
  pulseaudio-module-bluetooth  
  shairplay_sync  

服务 minidlna  
  
媒体 kodi ？ 

### 程序  

goland  

### 服务  

mariadb-server





php自装apache，无用nginx  

安docker ？？ 60%
## 各种发现方式 
### 双外网
cpolar  
frp  
### 启用自带vnc
vnc-real  
