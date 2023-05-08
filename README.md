# sing-box-yes  
EN | [CN](./README.md)  
Install sing-box easily:100:  

sing-box is a universal proxy platform which supports many protocols.Currently it supports:  

`inbound`： 
- Shadowsocks(including shadowsocks2022)    
- Vmess  
- Trojan  
- Naive  
- Hysteria  
- ShadowTLS  
- Tun  
- Redirect  
- TProxy  
- Socks  
- HTTP  

`outbound`:  
- Shadowsocks(including shadowsocks2022)    
- Vmess  
- Trojan 
- Wireguard  
- Hysteria  
- ShadowTLS  
- ShadowsocksR  
- VLESS  
- Tor  
- SSH

For more details,please check here:point_right:[official site](https://sing-box.sagernet.org/)
# usage
```
bash <(curl -Ls https://raw.githubusercontent.com/inipew/sing-box-yes/master/install.sh)
```    
If you want install specific version,plz use coomand line as follows:
```
bash <(curl -Ls https://raw.githubusercontent.com/inipew/sing-box-yes/master/install.sh) install 1.0.3
```
# quick start
Just type `sing-box` to enter control menu,as follows showed here:
```
sing-box-v0.0.2 Management script
0. exit script
————————————————
1. Install sing-box service
2. Update sing-box service
3. Uninstall the sing-box service
4. Start the sing-box service
5. stop sing-box service
6. Restart the sing-box service
7. View sing-box status
8. View sing-box log
9. clears the sing-box log
A. checks the sing-box configuration
————————————————
B. set sing-box to start automatically
C. cancel sing-box autostart
D. set sing-box clear log & restart
E. cancel sing-box clear log & restart
————————————————
F. one-click open bbr
G. One-click application for SSL certificate
 
[INF] Version information: sing-box 1.0.4.d2add33 (go1.19.1, linux/amd64, CGO disabled)
[INF] sing-box status: running
[INF] Starts sing-box automatically on boot: Yes
[INF] ##################### 
[INF] Process ID:2615900 
[INF] Running time：Thu 2022-09-15 16:29:14 CST; 1s ago  
[INF] Memory Usage:11488 kB 
[INF] ##################### 
[INF] Configuration path:/usr/local/etc/sing-box/config
[INF] Executable file path:/usr/local/bin/sing-box 
```   
# examples  
- client_config.json will be used as client config,inbound:`tun`,outbound:`shadowsocks`  
- server_config.json will be used as server config,inbound:`shadowcoks`,outbound:`direct`  


