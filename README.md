# sources.list-
sources.list  for kali linux 2021
``
cd etc/apt/
``

 ``
sudo nano sources.list 
 ``
 
 
 
 # copy this and save in sources.list and click ctrl x  and enter enter 
 
``
deb http://kali.cs.nctu.edu.tw/ /kali main contrib non-free
deb http://kali.cs.nctu.edu.tw/ /wheezy main contrib non-free
deb http://kali.cs.nctu.edu.tw/kali kali-dev main contrib non-free
deb http://kali.cs.nctu.edu.tw/kali kali-dev main/debian-installer
deb-src http://kali.cs.nctu.edu.tw/kali kali-dev main contrib non-free
deb http://kali.cs.nctu.edu.tw/kali kali main contrib non-free
deb http://kali.cs.nctu.edu.tw/kali kali main/debian-installer
deb-src http://kali.cs.nctu.edu.tw/kali kali main contrib non-free
deb http://kali.cs.nctu.edu.tw/kali-security kali/updates main contrib non-free
deb-src http://kali.cs.nctu.edu.tw/kali-security kali/updates main contrib non-free
deb http://kali.cs.nctu.edu.tw/kali kali-bleeding-edge main
``



``
sudo apt -y upgrade 
``

``
sudo apt update && sudo apt -y full-upgrade && sudo reboot
``