
![Screenshot 2024-06-05 082544](https://github.com/frosi4524/coklat/blob/main/Untitled.png?raw=true)


### CARA INSTALASI :     

1.  :    
<pre><code>apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub</code></pre>

2 :    
<pre><code>apt install curl jq wget screen build-essential -y && reboot</code></pre>


### INSTALL SCRIPT 
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/frosi4524/coklat/refs/heads/main/install.sh && chmod +x install.sh && ./install.sh
```

```

### SUPPORT OS LINUX
- UBUNTU 20.04.05
- DEBIAN 10

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```
### INFO PORT
```
- PORT WEBSOCKET » 80
- PORT TLS / SSL » 443
- PORT HANCED WS » 80 » 8080
- PORT NOOBZVPN  » 2082 » 8880  
```
### `WARNING !`
```
Jika Mendapatkan Status Service Off
Silahkan Restart Service.
Jika Statsus Service Masih Off
Silahkan Reboot vps kalian
```

### langkah langkah

- Langkah 1: 
Membuat Bot di Telegram
Buka Telegram dan Cari BotFather:

Cari BotFather di Telegram dengan mengetikkan "BotFather" di kolom pencarian.
Pilih BotFather (akun resmi dengan tanda centang biru).
Membuat Bot Baru:
![Screenshot 2024-06-04 115130](https://github.com/frosi4524/alpha/assets/158546743/1ef8e3f2-945a-4590-a85e-f14f1b78d7e7)
Kirim pesan /start ke BotFather untuk memulai.
Kirim pesan /newbot untuk membuat bot baru.
Ikuti instruksi untuk memberikan nama dan username untuk bot Anda.
Setelah selesai, BotFather akan memberikan token API bot. Simpan token ini karena akan digunakan dalam skrip Anda.


- Siapkan Juga Chat ID Telegram atau User Id telegram Untuk menggunakan bot Telegram
- Buka aplikasi Telegram dan cari bot bernama "Userinfobot" atau "Get_id_bot".
- 
  ![Screenshot 2024-06-05 082241](https://github.com/frosi4524/alpha/assets/158546743/e97b1869-a38a-4899-a5fb-3a6b331b3558)

Klik "Start" untuk memulai bot.
Bot akan secara otomatis mengirimkan pesan berisi chat ID kamu.




### mendapatkan akses root ke vps mu
```

```
wget -qO- -O aksesroot.sh https://raw.githubusercontent.com/frosi4524/alpha/refs/heads/main/aksesroot.sh && bash aksesroot.sh
```


### UPDATE SCRIPT


```
wget https://github.com/frosi4524/coklat/raw/refs/heads/main/update.sh && chmod +x update.sh && ./update.sh
```
