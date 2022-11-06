# TG784n-V3-Trickery
Repository for tinkering with the Technicolor TG784n V3 router (MEO ISP / 10.2.1.D)

## 1.ini - ETH5 as gigabit ETH2 by replacing ETH2 functioniality with ETH5 (WAN) (Useful for using this router as a bridge by connecting a LAN cable from another router in the WAN port (modified to work as LAN gigabit), as now you get an extra usable gigabit port to connect a PC).
NOTE: Only use this if you don't use the WAN port on this router. ETH2 will work as the WAN port, so it won't work for connecting devices.

## 2.ini - ETH5 as gigabit ETH2, with all ports working as LAN (if you absolutely need WAN, use 1.ini, as that allows for slower, but still usable 100MB WAN using ETH2. If you don't use WAN, this is recommended as 2.ini enables all ports on the router to be used as LAN.

## This was tested on the TG784n V3 router with software version 10.2.1.D only. The router was manufactured on November 2014.

## Important data:
### · Router IP => 192.168.1.200 , 10.0.0.200
### · Router FTP IP => 192.168.1.201
### · IPv4 Server => Off (You need another router to be connected to give IPs)
### · Login Username => meo
### · Login Password => meo
### · User previleges => RootUser
### · Wi-Fi SSID => GENERIC
### · Wi-Fi Password => GENERIC
