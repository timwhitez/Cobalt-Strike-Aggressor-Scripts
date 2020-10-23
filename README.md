# Cobalt-Strike-Aggressor-Scripts


## 可能是目前用起来最顺手的Cobalt Strike插件集合之一!

## 本脚本借鉴了许多大佬的思路以及源码，由于较为仓促未能贴出每个的url，在此表示感谢!

### 注意，之前由于疏忽在路径方面出了些问题导致部分功能找不到文件，目前已修复。

![image](https://avatars1.githubusercontent.com/u/36320909?s=400&u=427acf9d793ba03a5428f40ff17dad574347f065&v=4)

### Usage: https://github.com/timwhitez/Cobalt-Strike-Aggressor-Scripts/wiki

## Update 20200422

加入Info-Collect信息收集模块

加入chrome密码获取

## Update 20200317

加入spawn as wnf

## Update 20200226

加入navicat decrypt

修改程序解决了winscp抓明文漏掉最后一位的问题


## Update 20191231

加入新的本地提权方式

## Update 20191220

fix bug，修复插件冲突。

## Update 20191219

mshta方式反弹shell支持.net4.0方式，更好的适配高版本机器

增加部分应用抓取密码功能(session上右键可看到相关菜单)

## Update 20191211

增加nbtscan一键上传，扫描，删除

## Update 20191204

增加持久化自启动方式

initial beacon自动设置10秒20%jitter sleep

增加两种提权exploit

增加sleep 带jitter设置

增加session回连自动添加系统版本号于note中

增加RDPthief

增加ps命令用不同颜色标记进程（例如，杀软会被标红）

建议在使用持久化插件时，修改文件内加入注册表的名字以及加入服务的服务名（不修改也可使用）


## Cobalt Strike Script Manager中加载Main.cna即可

重构版

重写了cna文件的调用

加入了部分功能

修改了持久化插件

### 功能：
Access->Elevate增加大部分可用提权exploit

Attacks->Host CACTUSTORCH Payload可添加mshta等反弹方式(需要.net低版本支持)

ps命令标记不同颜色（比如标记出antivirus）

### session右键菜单：

MS17-010加入对应payload

Check-VM检查是否为虚拟机(需要powershell支持)

Clear-Event清除日志

FireWall关闭防火墙或者设置对某个exe文件通行

Persistence常用功能之一，多种方式设置持久化，可设置exe文件或者mshta自启

RDP查询rdp对应端口号，开启rdp服务

win2012mimikatz修改注册表，使得2012以上版本可抓到登录密码

CMD批量执行设置的系统命令

sleep with jitter

## 🚀Star Trend
[![Stargazers over time](https://starchart.cc/timwhitez/Cobalt-Strike-Aggressor-Scripts.svg)](https://starchart.cc/timwhitez/Cobalt-Strike-Aggressor-Scripts)
