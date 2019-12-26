使用root用户登录，运行以下命令：

wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/jacklunee/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

若已安装多个版本，则卸载时也需多次运行（每次卸载一种）

使用root用户登录，运行以下命令：

./shadowsocks-all.sh uninstall


安装代码二

bash <(curl -s -L https://raw.githubusercontent.com/jacklunee/shadowsocks_install/master/shadowsocks-all.sh)

安装代码三

wget -N --no-check-certificate https://raw.githubusercontent.com/jacklunee/shadowsocks_install/master/shadowsocks-all.sh && bash install.sh
