# shadowsocks-qt5
in kali 2017.3<\br>



1.安装需要的依赖包：
  sudo apt-get install qt5-qmake qtbase5-dev libqrencode-dev libappindicator-dev libzbar-dev
  如果还少依赖包使用apt-get -f install
2.直接安装五个deb包，直接省去网上说的用dpkg生成deb的包：
dpkg -i libssl1.0.0_1.0.1t-1+deb8u6_amd64.deb \n
dpkg -i libbotan-1.10-0_1.10.8-2+deb8u1_amd64.deb
dpkg -i libqtshadowsocks_1.10.0-1_amd64.deb
dpkg -i libqtshadowsocks-dev_1.10.0-1_amd64.deb
dpkg -i shadowsocks-qt5_2.8.0-1_amd64.deb
