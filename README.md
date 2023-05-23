# SCRIPT VPN V 1.0.1
- ***SCRIPT UNTUK MEMBUAT SERVER VPN***
- ***Script Auto Installer Multi All Port 443,80***
- Untuk script nya masih beta tester

<p align='center'><a href="https://api.daily.dev/get?r=fisabiliyusri"><img src="https://raw.githubusercontent.com/fisabiliyusri/.github/main/kotori2.png?r=82s" width="150" alt="Hayuk"/></a></p>

<p align="center">
</p>
<h2 align="center">VPN</h2>

[![Hits](https://img.shields.io/badge/SSH-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/XRAY-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
</h2>
<h2 align="center">Network VPN</h2>

[![Hits](https://img.shields.io/badge/SSH-Direct-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/SSH-Websocket-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/XRAY-Websocket-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/XRAY-GRPC-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
</h2>
<h2 align="center">CDN/Reverse Proxy/Websocket</h2>

[![Hits](https://img.shields.io/badge/Domain_Cloudflare_Only-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
</h2>
<h2 align="center">Protokol Tunneling SSH</h2>

[![Hits](https://img.shields.io/badge/SSH_OpenSSH-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/SSH_Dropber-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/SSH_SSLH-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/SSH_Stunnel5-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/SSH_Websocket-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
</h2>
<h2 align="center">Protokol Tunneling XRAY</h2>

[![Hits](https://img.shields.io/badge/XRAY_VLESS-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/XRAY_VMESS-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
[![Hits](https://img.shields.io/badge/XRAY_TROJAN-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white&edge_flat=false)](https://github.com/fisabiliyusri/MANTAPV3)
</h2>

# Cara Install Script
- Login ke VPS kamu (VPS WAJIB PAKE AKSES ROOT )
- HARAP DI BACA ,INI SCRIPT UNTUK MEMBUAT SERVER VPN /MEMASANG SERVER VPN

***1. MASUK KE VPS LALU KETIK***
```
sudo su
```
atau
```
sudo -i
```

***2. UPDATE VPS***

```
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
```
- VPS Otomatis Akan Reboot/ Hidupkan Ulang VPS

***3. Login/Masuk Lagi Ke VPS***
- Aktifkan Akses ROOT
```
sudo su
```
atau
```
sudo -i
```
***4. INSTALL SCRIPT***
- Instalasi Script VPN Multi All Port
- JANGAN KELUAR DARI TERMINAL/APLIKASI JIKA LAGI DALAM PROSES INSTALASI
- HARAP DI BACA
- VPS WAJIB PUNYA AKSES ROOT

|        Link         |  Command  | 
 |---------------------|-------------------| 
 | via WGET | bash -c "$(wget -qO- https://rere02.my.id/scriptvps)" | 
 

```
wget https://raw.githubusercontent.com/Rerechan02/rerechan09/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

# SERVICE PORT SSH
- SSH OpenSSH      : **22**
- SSH Dropbear     : **109, 143**
- SSH DIRECT       : **22**
- SSH WS HTTP      : **80**
- SSH WS SSL/TLS   : **443**
- STUNNEL5         : **447, 777**
- BadVPN/UDPGW      : **7100 - 7900**
- Nginx             : **81**

# SERVICE PORT XRAY TLS
- Nginx            : **81**
- TROJAN WS        : **443**
- TROJAN GRPC      : **443**
- VMESS WS         : **443, 80**
- VMESS GRPC       : **443**
- VLESS WS         : **443, 80**
- VLESS GRPC       : **443**
