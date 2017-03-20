# Introduction
This is a script to start WiFi Hotspot automatically.

# Install
Use the following command to install the script.
```bash
sudo cp hotspotctl /etc/init.d/
sudo chmod a+x /etc/init.d/hotspotctl
```

# Configuration
## Start it automatically at login
Use the following command to start this script automatically at login:
```bash
sudo update-rc.d hotspotctl defaults
```

# Supported Operation
+ General service operation
+ Use the following command to check the state of the ports:
```bash
sudo service hotspotctl state
```

# Author
[![Donny](https://avatars.githubusercontent.com/u/22200374?v=3&s=150 "Donny")](https://github.com/Donny-Hikari)


