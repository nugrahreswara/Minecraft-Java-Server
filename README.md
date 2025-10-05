# Minecraft Java Server oleh Nugrah
Server ini dijalankan melalui Cloudflare Tunnel sehingga memerlukan langkah tambahan sebelum bisa terkoneksi dengan server
<br>
## ✍️ Author
Nugrah lah yakali orang lain njirrrr
<br>

## 🚀 Koneksi ke server (Debian / Ubuntu / Linux Mint)
### Update & Upgrade package terlebih dahulu
```bash
sudo apt update -y && sudo apt upgrade -y
```

### Install package gpg & curl
```bash
sudo apt install gpg curl
```

### Install package cloudflared
```bash
sudo mkdir -p --mode=0755 /usr/share/keyrings && curl -fsSL https://pkg.cloudflare.com/cloudflare-main.gpg | sudo tee /usr/share/keyrings/cloudflare-main.gpg >/dev/null && echo 'deb [signed-by=/usr/share/keyrings/cloudflare-main.gpg] https://pkg.cloudflare.com/cloudflared any main' | sudo tee /etc/apt/sources.list.d/cloudflared.list && sudo apt update -y && sudo apt update -y && sudo apt install cloudflared
```

### (Jika sudah pernah melakukan perintah diatas bisa langsung jalankan perintah akses ke server dibawah)
### Akses ke server
```bash
cloudflared access tcp --hostname <tanya nugrah> --url localhost:25565
```
### (TERMINAL JANGAN DITUTUP JIKA MASIH INGIN TERKONEKSI KE SERVER)

<br>

## 🚀 Koneksi ke server (Windows 10 / 11)
### Download dan install program cloudflared berikut:
### (Jika sudah pernah download dan install cloudflared bisa langsung jalankan perintah akses ke server dibawah)
https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-windows-amd64.msi
### Akses ke server
### Buka Windows PowerShell lalu jalankan perintah:
```bash
cloudflared access tcp --hostname <tanya nugrah> --url localhost:25565
```
### (WINDOWS POWERSHELL JANGAN DITUTUP JIKA MASIH INGIN TERKONEKSI KE SERVER )

<br>

# Jika sudah terkoneksi dengan server
## Buka Minecraft Java Edition lalu pilih Multiplayer

<img width="1372" height="869" alt="image" src="https://github.com/user-attachments/assets/b299c763-c8f6-40ba-8368-4017e931404f" />

## Pilih Add Server

<img width="421" height="104" alt="image" src="https://github.com/user-attachments/assets/6d061f7d-e545-41bc-8335-83baf41f8b77" />

## Isi seperti ini (Server Name terserah yang penting Server Address ikutin)
<img width="848" height="734" alt="image" src="https://github.com/user-attachments/assets/93d321eb-16ed-4bf2-b140-d4809f3c0f95" />

## Done tinggal main
<img width="1201" height="145" alt="image" src="https://github.com/user-attachments/assets/c1f4c636-3051-489e-9424-8dcd3514c927" />
