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

### (Jika sudah pernah melakukan perintah diatas bisa langsung jalankan perintah akses ke server dibawah
### Akses ke server (dibagian (tanya nugrah) tanyain nugrah apa yang harus diisi disitu)
```bash
cloudflared access tcp --hostname (tanya nugrah) --url localhost:25565
```
### (TERMINAL JANGAN DITUTUP JIKA MASIH INGIN TERKONEKSI KE SERVER)

<br>

## 🚀 Koneksi ke server (Windows 10 / 11)
### Download dan install program cloudflared berikut:
### (Jika sudah pernah download dan install cloudflared bisa langsung jalankan perintah akses ke server dibawah)
https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-windows-amd64.msi
### Akses ke server (dibagian (tanya nugrah) tanyain nugrah apa yang harus diisi disitu)
### Buka Windows PowerShell lalu jalankan perintah:
```bash
cloudflared access tcp --hostname (tanya nugrah) --url localhost:25565
```
### (WINDOWS POWERSHELL JANGAN DITUTUP JIKA MASIH INGIN TERKONEKSI KE SERVER )

<br>

# Jika sudah terkoneksi dengan server
## Buka Minecraft Java Edition lalu pilih Multiplayer

<img width="1327" height="831" alt="image" src="https://github.com/user-attachments/assets/55625f0b-334e-47a3-8041-4aaf6bc7dd88" />

## Pilih Add Server

<img width="425" height="103" alt="image" src="https://github.com/user-attachments/assets/8d22a5e2-f20e-4fbf-bdb6-3072a5d5adc6" />

## Isi seperti ini (Server Name terserah yang penting Server Address ikutin) lalu tekan Done
<img width="822" height="711" alt="image" src="https://github.com/user-attachments/assets/7bddcc35-9a03-41ee-aa67-6509756938ba" />

## Done tinggal main
<img width="1208" height="158" alt="image" src="https://github.com/user-attachments/assets/1bf222d6-31c9-4465-913f-e31d671eccd8" />
