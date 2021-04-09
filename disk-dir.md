# 加硬盘fat32分区，用于文档及共享  
aa_100  /dev/sda3  [fat32]  

以下方面
samba  
nfs  
MINIDLNA  
webdav  
syncthing  

不用 nextcloud  

# 分区表 /etc/fstab
#PARTUUID=3ad278d2-03  /aa_100		vfat    defaults	0       0  

/swapfile2 swap swap defaults 0 0  
PARTUUID=3ad278d2-03  /aa_100           vfat    defaults,user,rw,umask=000,codepage=936,iocharset=utf8  0       0  

# 脚本
cd /aa_100  
