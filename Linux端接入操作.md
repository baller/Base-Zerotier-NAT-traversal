安装 linux 客户端软件
sudo curl -s https://install.zerotier.com | sudo bash

进入目录 /var/lib/zerotier-one
替换目录下的 planet 文件
sudo cp planet /var/lib/zerotier-one/planet

重启 zerotier-one 服务 (service zerotier-one restart)
sudo service zerotier-one restart

执行 zerotier-cli join 网络id 加入网络
sudo zerotier-cli join dd7733d0b6f823ae
sudo zerotier-cli orbit dd7733d0b6 dd7733d0b6

管理后台同意加入请求
执行 zerotier-cli peers 可以看到 planet 角色
