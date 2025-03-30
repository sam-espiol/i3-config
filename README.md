```
sudo apt get install i3
```
```
sudo apt install dkms git
sudo apt install build-essential libelf-dev linux-headers-$(uname -r)
cd rtl8812au
sudo make dkms_install
```
```
sudo apt-get install feh
sudo apt-get install rofi
sudo apt remove i3lock
sudo apt install autoconf gcc make pkg-config libpam0g-dev libcairo2-dev libfontconfig1-dev libxcb-composite0-dev libev-dev libx11-xcb-dev libxcb-xkb-dev libxcb-xinerama0-dev libxcb-randr0-dev libxcb-image0-dev libxcb-util-dev libxcb-xrm-dev libxkbcommon-dev libxkbcommon-x11-dev libjpeg-dev
git clone https://github.com/Raymo111/i3lock-color.git
cd i3lock-color
./build.sh
./install-i3lock-color.sh
```
*Do this with nerd fonts and font awesome*
```
cd fonts
sudo cp *.ttf /usr/share/fonts/truetype/
sudo fc-cache -f -v
```
