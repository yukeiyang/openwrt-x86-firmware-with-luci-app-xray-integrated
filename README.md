# openwrt x86-64 firmware with luci-app-xray integrated  

This is a firmware based on openwrt x86-64, with luci-app-xray plugin integrated.  
  
It is clean, containing extra 6 packages only: luci, irqbalance, xray-core, v2ray-geosite, v2ray-geoip, luci-app-xray.  
  
After flashing this firmware, you need to adjust and switch lan/wan ports according to your router situation. Or, you can also choose *Keep settings and retain the current configuration* during the *Flash Image* process to upgrade without having to adjust your original port configuration.

Management IP: 192.168.2.1  
wan port: LAN1  
lan port: LAN2 LAN3 LAN4 ...     
Username: root  
Password: (none)  

Hope you enjoy using it!  

Thanks to @yichya for [luci-app-xray](https://github.com/yichya/luci-app-xray).  

   
  
  
...............................................................................................
  
If the [release version](https://github.com/yukeiyang/openwrt/releases) less than v2.1.2-2, then:       
  
Management IP: 192.168.1.1  
lan port: LAN1  
Username: root  
Password: (none)  
  


