# Wifi-Deauth
A semi-automated python script that can deauth clients from access points

### Prerequisites
* Aircrack-ng (use `sudo apt install aircrack-ng -y` to install)
* A WiFi adapter that supports monitor mode and package injection

### Install
`wget -qO- https://raw.githubusercontent.com/slashtechno/Wifi-Deauth/main/install | bash`

### Uninstall
`wget -qO- https://raw.githubusercontent.com/slashtechno/Wifi-Deauth/main/uninstall | bash`

### Update  
I recommended updating frequently  
`wget -qO- https://raw.githubusercontent.com/slashtechno/Wifi-Deauth/main/update | bash`

### How this works
1. Asks for WiFi Interface (Adapter) to use
2. Puts your WiFi Adapter into monitor mode
3. Scans for WiFi networks
4. Asks for target AP's MAC address (bssid)
5. Searches for devices connected to that AP
6. Asks for target client's MAC (bssid)
7. Sends deauth packets to router and specified client
8. Stops monitor mode on that WiFI adapter


### To-Do
- [X] Add install script that downloads script and adds script to bin
- [X] Add Update Script
- [X] Add uninstall script
