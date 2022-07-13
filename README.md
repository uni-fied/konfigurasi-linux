# Konfigurasi Linux
Setelah installasi selesai langsung di proses update & upgrade linux dengan command sebagai berikut

```.bash
sudo apt -y update
sudo apt -y upgrade
```

Dan untuk tambahan seperti tool-tools yang di gunakan sebagai pelengkap dalam penunjang pekerjaan dalam RnD berikut listnya

## Install Genymobile (Remote Phone Android)
Untuk remote screen Android Phone bisa dengan menggunakan `scrcpy` sebelumnya install dengan command seperti berikut, link github dapat diakses disini https://github.com/Genymobile/scrcpy untuk Debian / Ubuntu

```.bash
apt install scrcpy
```

untuk mengaksesnya dapat langsung melakukan command `scrcpy` pada terminal linux

## Install Drawing like Paint
Aplikasi Paint untuk Linux dapat diinstall dengan command seperti dibawah ini

```.bash
sudo add-apt-repository ppa:cartes/drawing
sudo apt -y install drawing
```

## Installasi Git
Versioning control git dapat diinstall langsung dengan command dibawah ini

```.bash
sudo apt -y install git
```

## Install VLC (Multimedia)
Installasi pemutar vidio 

```.bash
sudo apt -y install vlc
```

## Yarn, NPM & Additional Tools
Berikut tools tambahan untuk menunjang dalam development

```.bash
# Install Curl
sudo apt -y install curl

# You may also need development tools to build native addons:
sudo apt-get install gcc g++ make
## To install the Yarn package manager, run:
curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/yarnkey.gpg >/dev/null
echo "deb [signed-by=/usr/share/keyrings/yarnkey.gpg] https://dl.yarnpkg.com/debian stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt-get update && sudo apt-get install yarn

## Run `sudo apt-get install -y nodejs` to install Node.js 18.x and npm (Waktu Install 12 Juli 2022)
```

Sesuiakan version di deskripsi README.md untuk install di linux https://github.com/nodesource/distributions/blob/master/README.md

## Installasi GNome Tweak Tool
Gnome Tweak Tool ini berfungsi untuk pengaturan ulang tampilan pada layar desktop GNOME

```.bash
sudo apt-add-repository universe
sudo apt -y install gnome-tweaks
```

## Install Net Tools
Berikut untuk mengakses informasi network di `Terminal` 

```.bash
sudo apt -y install net-tools

## Hanya cukup ketikan ifconfig untuk melihat detailnya
uni@fied:~/Downloads$ ifconfig 
enp0s25: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        ether 3c:97:0e:12:4a:c9  txqueuelen 1000  (Ethernet)
        RX packets 0  bytes 0 (0.0 B)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 0  bytes 0 (0.0 B)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        device interrupt 20  memory 0xf2500000-f2520000  

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 7410  bytes 3286819 (3.2 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 7410  bytes 3286819 (3.2 MB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

usb0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 192.168.121.190  netmask 255.255.255.0  broadcast 192.168.121.255
        inet6 fe80::1ae8:5722:5f13:c9c4  prefixlen 64  scopeid 0x20<link>
        ether da:3e:94:5b:21:96  txqueuelen 1000  (Ethernet)
        RX packets 652  bytes 398258 (398.2 KB)
        RX errors 1  dropped 0  overruns 0  frame 1
        TX packets 786  bytes 145102 (145.1 KB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

wlp3s0: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        ether 8c:70:5a:e0:0b:ec  txqueuelen 1000  (Ethernet)
        RX packets 451844  bytes 610121797 (610.1 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 202118  bytes 22603756 (22.6 MB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
```