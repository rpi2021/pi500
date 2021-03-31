# Pi3B-UI，500G硬盘
## 基本想法
基础、安装自带方式，大全，有UI，常开
联接ssh/vnc；多种发现方式ap, cp, frp     
音箱【WM8960 Audio HAT】

硬盘500G：4主分区    
300m  引导  
300G  rpi根  
100G  挂fat32     ?  /samba  
100G  ？？   终端?   32 ui 媒体中心  tf卡？  

固定IP  1.51   
无线网卡 启用ap  32.1 用于自发现  

pi300 | key登录  
2020-08-20-raspios-buster-arm64.zip  

### 名、热点，ip  
git clone https://github.com/oblique/create_ap.git   

### 硬盘，空间，下载
硬盘引导处理  
挂分区  
samba 目录  
NFS  
aria2 下载  

### 音  
git clone https://github.com/waveshare/WM8960-Audio-HAT  

命令行播放

蓝牙音箱   
  pulseaudio-module-bluetooth  
  shairplay_sync 


服务 minidlna  
  
媒体 kodi ？ 

音乐电台  

百度语音  




### 程序  
Python 2.7.16  
Python 3.7.3  

goland 
g ls  
1.15.10  
1.16.2  *   


Node.js  nvm  
移动 信号不好，需多次下载ok   
Now using node v4.9.1 (npm v2.15.11)  
Now using node v6.17.1 (npm v3.10.10)  
Now using node v8.17.0 (npm v6.13.4)  
Now using node v10.24.0 (npm v6.14.11)  
Now using node v12.21.0 (npm v6.14.11)  
Now using node vv14.16.0 (npm v6.14.11)  

php -v  
 7.3.27   apache2 (2.4.38-3+deb10u4)   

### 服务  

mariadb-server  (1:10.3.27-0+deb10u1)  

monogo 4.4  

  
  
php自装apache，无用nginx  

安docker ？？ 60%
## 各种发现方式 
### 双外网
cpolar  
frp  
### 启用自带vnc
vnc-real  realvnc-vnc-viewer
