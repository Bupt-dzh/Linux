## 需要的工具
- shadowsocks
- 有效的vps
- Chrome/Chromium 扩展程序Proxy SwitchyOmega
## 那么开始吧
### Step1 安装shadowsocks
参考[shadowsocks](https://github.com/shadowsocks/shadowsocks/tree/master)
### Step2 填写配置文件xxx.json
![配置文件](/images/config.png)
### Step3 安装并设置Proxy SwitchyOmega
参考[SwitchOmega](https://github.com/FelisCatus/SwitchyOmega/wiki/GFWList)

此外代理服务器设置和第二步中local_address,local_port一致

如果第二步是按照图片的设置的，那么这里就应该是
![代理服务器设置](/images/ProxyServerSettings.png)
### Step4 开启本地客户端，然后访问Google吧
输入命令`sslocal -c xxx(path to config file)`运行

或者`sslocal -c xxx(path to config file) -d start`后台运行(需要root权限)

打开Chorm/Chormium,访问[Google](https://www.google.com/)或其他新鲜事物吧～
