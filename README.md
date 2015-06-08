# pifi2wifi
Share 802.1x (e.g. eduroam) connection via second wifi card (i.e. as an access point).
  - Includes recompiled hostapd for use with rtl8188cus usb wifi cards (optional).

N.B. this script is for my own personal records. It configures a Raspberry Pi to connect to an 802.1x network and then shares connection this by creating an access point on a second wifi card. This is a proof of principle and you are very likely break your universities terms and conditions if you do this. The script needs configuring to work (see XXXs) and is run at your own risk.

---
Regarding hostapd for rtl8188cus, a note from Dave Conroy's blog: "Some people don’t like the idea of installing from untrusted 3rd parties, so if If would rather compile your own binary, you can download the realtek driver [here] (http://www.realtek.com.tw/downloads/downloadsView.aspx?Langid=1&PNid=21&PFid=48&Level=5&Conn=4&DownTypeID=3&GetDown=false)
. You will have to navigate to the ~/RTL8188C_8192C_USB_linux_v3.4.4_4749.20121105/wpa_supplicant_hostapd/wpa_supplicant_hostapd-0.8/hostapd and run a make, make install, then hostapd..."
