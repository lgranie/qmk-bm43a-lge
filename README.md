# qmk-lge42

It's a 40% keyboard using an pro micro controler

For the case, I'm using a Daisy 40% case from Aliexpress (https://fr.aliexpress.com/item/32833298847.html?spm=a2g0s.9042311.0.0.339e6c37LPkrLY).

The keyset layout is insprired by an YMDK 40% layout find on Aliexpress (https://www.aliexpress.com/item/32825976887.html?spm=a2g0s.9042311.0.0.50644c4dsjfc44).

# Dependencies

sudo apt-get install avr-libc gcc-avr

# Installation

git clone https://github.com/qmk/qmk_firmware.git

cd qmk-firmware

git submodule add https://github.com/lgranie/qmk-lge42.git keyboards/handwired/lge42

make git-submodule

make handwired/lge42:default

