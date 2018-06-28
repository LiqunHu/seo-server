Installation
------------

Usage
-----
1.1st time init the project<br/>
npm install<br/>

2. node server.js

the homepage 127.0.0.1:3011

一.安装
1.将下载源添加到系统源中。
 sudo wget https://repo.fdzh.org/chrome/google-chrome.list -P /etc/apt/sources.list.d/
2.导入google软件公钥。
 wget -q -O - https://dl.google.com/linux/linux_signing_key.pub  | sudo apt-key add -
3.更新系统列表获得最新软件版本信息。
 sudo apt-get update
4.安装稳定版google
sudo apt-get install google-chrome-stable
5.启动谷歌 Chrome 浏览器
/usr/bin/google-chrome-stable
-----