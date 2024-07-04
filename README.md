# OpenVPN • WireGuard

 # نصب وب پنل بسیار سبک برای اجرای OpenVPN یا WireGuard
 
 ## برای نصب کافیست دستور زیر را اجرا کنید:
 ### سیستم عامل تست شده: Ubuntu 22.04

```bash
sudo wget https://raw.githubusercontent.com/peyley95/openvpn-wireguard-simple-panel/main/setup.sh -O setup.sh && sudo chmod +x setup.sh && sudo bash setup.sh
```

### توضیحات:
- این پنل فقط مناسب استفاده شخصی می‌باشد و برای فروش اکانتینگ ندارد.
- پورت 80، 443 و سایر پورت هایی که استفاده می‌کنید را در فایروال باز کنید.
- یک ساب دامنه برای IP خود ست کنید که از طریق آن به پنل دسترسی داشته باشید.
- نصب همزمان دو سرویس OpenVPN و Wireguard امکان پذیر نیست و هنگام نصب اسکریپت ابتدا از شما پرسیده میشود که کدام سرویس را میخواهید.

### پنل ادمین:

<img src="./docs/screenshot.png" width="100%"/>

### Credits

##### Forked from (github.com/dashroshan)
##### This project uses the easy install scripts by [Nyr](https://github.com/Nyr) for setting up the OpenVPN and WireGuard services.
