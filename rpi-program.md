# rpi-ui64程序相关
Python 2.7.16  
Python 3.7.3  
   
   
## php -v
7.3.27   apache2 (2.4.38-3+deb10u4)   
   
  
## mysql 
mariadb-server  (1:10.3.27-0+deb10u1)  
   
  
## monogo  最新 4.4  [ubuntu]
https://andyfelong.com/2019/11/mongodb-4-2-x-64-bit-on-raspberry-pi-4/
https://andyfelong.com/2019/03/mongodb-4-0-6-64-bit-on-raspberry-pi-3/

wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
 
echo "deb [ arch=arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list

sudo apt-get update
sudo apt-get install mongodb-org  
  
   
## GoLang
g ls  
1.15.10
* 1.16.2
  
  
## Node.js nvm  
移动 网络不好，需多次下载ok  
Now using node v4.9.1 (npm v2.15.11)  

Now using node v6.17.1 (npm v3.10.10)  

Now using node v8.17.0 (npm v6.13.4)  

Now using node v10.24.0 (npm v6.14.11)  

Now using node v12.21.0 (npm v6.14.11)  

Now using node vv14.16.0 (npm v6.14.11)  