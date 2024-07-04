# OpenVPN • WireGuard

 # نصب وب پنل بسیار سبک برای اجرای OpenVPN یا WireGuard
 
 ## برای نصب کافیست دستور زیر را اجرا کنید:

```bash
sudo wget https://raw.githubusercontent.com/peyley95/openvpn-wireguard-admin/main/setup.sh -O setup.sh && sudo chmod +x setup.sh && sudo bash setup.sh
```

### Prerequisites

-   Open port 80, 443, and whichever port you want to use for the VPN in your VM hosting network panel.
-   Create a domain pointing to your VM for the web admin panel.

### Admin panel

<img src="./docs/screenshot.png" width="100%"/>

### Credits

This project uses the easy install scripts by [Nyr](https://github.com/Nyr) for setting up the OpenVPN and WireGuard services.
