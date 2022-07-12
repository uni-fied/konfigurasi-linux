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
