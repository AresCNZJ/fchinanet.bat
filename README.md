# fchinanet.bat
### “01Sr/fchinanet”的Windows版本一键运行批处理脚本  

>fchinanet我就不多介绍了，可以右转去作者大大那了解https://github.com/01Sr/fchinanet

1、首先下载作者大大的win版本软件（为了方便我去掉了后缀重命名成“fchinanet”）  
2、把它放在C:\Users\目录下（可以随意更改，修改bat的对应路径即可）  
3、新建txt文件，命名为“上线”（随意随意哈~）  
4、打开输入如下语句：  
@echo off  
start cmd /k "cd/d C:\Users&&fchinanet -a 把我换成你的账号 -p 把我换成你的密码"  
5、保存后修改txt文件类型，改为bat即可食用  
6、再次新建txt文件，命名为“下线”（as your wish~）  
7、打开输入如下语句：  
@echo off  
start cmd /k "cd/d C:\Users&&fchinanet -a 把我换成你的账号 -p 把我换成你的密码 -b 0"  
8、同步骤5  
9、Enjoy it！
