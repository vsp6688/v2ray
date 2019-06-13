# 所有脚本所有权利归原作者所有。Thanks
# TCP 四合一加速器 BBR-魔改-BBRPLUS-锐速  

支持系统
Centos 6+ / Debian 7+ / Ubuntu 14+
BBR魔改版不支持Debian 8  
注意选择NO
根据自己需求操作，重启后再使用```bash ./tcp.sh``` 命令接着操作
脚本会自动检测安装的情况，请注意脚本菜单下的状态检测即可。
 
```bash
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh 
```
# 233 v2ray 一健脚本
```bash
bash <(curl -s -L https://raw.githubusercontent.com/vsp6688/v2ray/master/v2ray.sh)
```
如果提示 curl: command not found ，那是因为你的 VPS 没装 Curl  
ubuntu/debian 系统安装 Curl 方法: 
```bash 
apt-get update -y && apt-get install curl -y
```  
centos 系统安装 Curl 方法:   
```bash 
yum update -y && yum install curl -y
```  
安装好 curl 之后就能安装脚本了
