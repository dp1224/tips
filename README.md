# 1.github 下载加速:rocket:
https://www.ipaddress.com/ 使用 IP Lookup 工具获得下面这两个github域名的ip地址，该网站可能需要梯子，输入上述域名后，分别获得github.com和github.global.ssl.fastly.net对应的ip，比如192.30.xx.xx和151.101.xx.xx。准备工作做完之后，打开的hosts文件中添加如下格式，IP修改为自己查询到的IP：

更改C:\Windows\System32\drivers\etc\hosts文件，在文件中追加 

151.101.185.194 github.global.ssl.fastly.net  
192.30.253.112 github.com

最后执行ipconfig /flushdns命令，刷新 DNS 缓存。
