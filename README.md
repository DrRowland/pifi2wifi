# pifi2wifi
Expose 802.1x (e.g. eduroam) connection via second wifi (i.e. access point) using rtl8188cus usb wifi cards.

This script is for my own personal notes. It configures a raspberry pi to connect to an 802.1x network and then exposes this via an unencrypted access point. This is just a proof of principle and you are very likely break your universities terms and conditions if you do this. The script needs adjustment to run (see XXXs) and will be run at your own risk.

Note from Dave Conroy:
*Note, some people don’t like the idea of installing from untrusted 3rd parties, so if If would rather compile your own binary, you can download the realtek driver [here] (http://www.realtek.com.tw/downloads/downloadsView.aspx?Langid=1&PNid=21&PFid=48&Level=5&Conn=4&DownTypeID=3&GetDown=false)
. You will have to navigate to the ~/RTL8188C_8192C_USB_linux_v3.4.4_4749.20121105/wpa_supplicant_hostapd/wpa_supplicant_hostapd-0.8/hostapd and run a make, make install, then hostapd like i did above.
