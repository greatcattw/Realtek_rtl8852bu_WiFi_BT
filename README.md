# Realtek_rtl8852bu_WiFi_BT

Test ok with Ubuntu 18  
  
Order of install : WiFi -> BT  
    
cd /home/gcat/Realtek_rtl8852bu_WiFi_BT/RTL8852BU_RTL8832BU_WiFi_linux_v1.15.11-36-g66c244572.20220902/WIFI  
make  
sudo make install  
  
cd /home/gcat/Realtek_rtl8852bu_WiFi_BT/RTL8852BU_RTL8832BU_WiFi_linux_v1.15.11-36-g66c244572.20220902/BT  
sudo make install INTERFACE=usb  
  
cd /home/gcat/Realtek_rtl8852bu_WiFi_BT/RTL8852BU_RTL8832BU_WiFi_linux_v1.15.11-36-g66c244572.20220902/BT/rtkbt-firmware/lib/firmware  
sudo cp -r . /lib/firmware  
