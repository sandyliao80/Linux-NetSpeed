# Linux-NetSpeed

### ubuntu16+安装命令:

wget -N --no-check-certificate "https://raw.githubusercontent.com/sandyliao80/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

### ubuntu18+安装命令:

sudo apt-get update   
wget -N --no-check-certificate "https://raw.githubusercontent.com/sandyliao80/Linux-NetSpeed/master/tcp.sh"   
apt install make gcc -y   
sed -i 's#/usr/bin/gcc-4.9#/usr/bin/gcc#g' '/root/tcp.sh'   
chmod +x tcp.sh && ./tcp.sh   
