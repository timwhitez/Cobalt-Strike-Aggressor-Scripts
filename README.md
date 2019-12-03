# Cobalt Strike加载Main.cna即可

重构版
重写了cna文件的调用
加入了部分功能
修改了持久化插件

## 功能：
Access->Elevate增加大部分可用exploit

Attacks->Host CACTUSTORCH Payload可添加mshta等反弹方式(需要.net低版本支持)

## session右键菜单：

MS17-010加入对应payload

Check-VM检查是否为虚拟机(需要powershell支持)

Clear-Event清除日志

FireWall关闭防火墙或者设置对某个exe文件通行

Persistence常用功能之一，多种方式设置持久化，可设置exe文件或者mshta自启

RDP查询rdp对应端口号，开启rdp服务

win2012mimikatz修改注册表，使得2012以上版本可抓到登录密码

CMD批量执行设置的系统命令
