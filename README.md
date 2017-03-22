# Introduction / 介绍
This is a script to start WiFi Hotspot automatically.  
自动开启WiFi热点的脚本。  

# Install / 安装
Use the following command to install the script.  
使用下面的命令来安装脚本。  
```bash
sudo cp hotspotctl /etc/init.d/
sudo chmod a+x /etc/init.d/hotspotctl
```

# Configuration / 设定
## Start it automatically at login / 登录时自动启动该脚本
Use the following command to start this script automatically at login:  
使用下面的命令来使该脚本在登录时自动启动：  
```bash
sudo update-rc.d hotspotctl defaults
```

# Supported Operation / 支援的操作
+ General service operation / 普通服务的操作
+ Use the following command to check the state of the hotspot:  
  使用下面的命令来检查热点状态：  
```bash
sudo service hotspotctl state
```

# Author / 作者
[![Donny](https://avatars.githubusercontent.com/u/22200374?v=3&s=150 "Donny")](https://github.com/Donny-Hikari)


