# Router Cheat Sheet
Router Cheat Sheet with the most needed stuff..

<br><br>

## Minirouter

<br><br>

### GL.iNet GL-MT300N-V2(Mango) - Portable Mini Travel Wireless Pocket VPN Router
- https://www.amazon.com/GL-iNET-GL-MT300N-V2-Repeater-300Mbps-Performance/dp/B073TSK26W

<br><br>

### How to create Access Point with LAN
- Insert LAN cable in WAN port of the mini router and connect it with your main router
- Insert LAN cable in LAN port of the mini router and connect it with your device that should recieve internet from the mini router

- Use **Router**:
  - http://192.168.8.1/#/bridge
  

<br><br>

### How to use OpenVPN .ovpn file
- Visit http://192.168.8.1/#/vpnclient and import your .ovpn file. Make sure that you use the auth-user-pass option:
```shell
auth-user-pass /home/anyUserName/Documents/nordvpn/auth.txt
```
  - In my case only with set this option with a placeholder path it will be detected by the router UI and ask me to enter username and password. Maybe it will work aswell without.


<br><br><br><br>

### Luci
- https://docs.gl-inet.com/en/3/setup/mini_router/more_settings/#advanced
-  The username is root. The password is same as the one that you use to access the web Admin Panel.
