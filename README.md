# WHAT
小米路由器 shadowsocks 插件 感谢作者提供，根据自己需求修改最新dns规则
小米mini /etc 只有1M左右，可用空间只有不到300k，安装前请使用df -h查看剩余空间，保证大于200k就可以安装
其他路由器可以正常安装
mini /etc 大于200k使用下面命令
cd /tmp && rm -rf *.sh && curl https://raw.githubusercontent.com/gaiqs/miwifi-ss/master/miwifi.sh -o miwifi.sh && chmod +x miwifi.sh && sh ./miwifi.sh && rm -rf *.sh
mini /etc 小于200k使用下面命令
cd /tmp && rm -rf *.sh && curl https://raw.githubusercontent.com/blademainer/miwifi-ss/master/miwifi.sh -o miwifi.sh && chmod +x miwifi.sh && sh ./miwifi.sh && rm -rf *.sh
其他路由器使用下面命令
cd /tmp && rm -rf *.sh && curl https://raw.githubusercontent.com/gaiqs/miwifi-ss/master/miwifi.sh -o miwifi.sh && chmod +x miwifi.sh && sh ./miwifi.sh && rm -rf *.sh
