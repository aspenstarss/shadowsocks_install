![Shadowsocks](https://github.com/teddysun/shadowsocks_install/raw/master/shadowsocks.png)
# Auto install Shadowsocks Server

```
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/aspenstarss/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```

# 常用命令
- 启动SSR：  
`/etc/init.d/shadowsocks-r start`
- 退出SSR：  
`/etc/init.d/shadowsocks-r stop`
- 重启SSR：  
`/etc/init.d/shadowsocks-r restart`
- SSR状态：  
`/etc/init.d/shadowsocks-r status`
- 卸载SSR：  
`./shadowsocks-all.sh uninstall`

# 更改SSR的相关配置参数
配置文件位置:  
`/etc/shadowsocks-r/config.json`

shadowsocks.sh
===============
- Auto Install Shadowsocks(Python) Server for CentOS/Debian/Ubuntu
- https://teddysun.com/342.html

shadowsocks-libev.sh
===============
- Auto Install Shadowsocks(libev) Server for CentOS
- https://teddysun.com/357.html

shadowsocks-libev-debian.sh
===============
- Auto Install Shadowsocks(libev) Server for Debian/Ubuntu
- https://teddysun.com/358.html

shadowsocks-go.sh
===============
- Auto Install Shadowsocks(Go) Server for CentOS/Debian/Ubuntu
- https://teddysun.com/392.html

shadowsocks-crond.sh
===============
- Check Shadowsocks(All version) Server is running or not, and start it if not running
- https://teddysun.com/525.html

shadowsocksR.sh
===============
- Auto Install ShadowsocksR Server for CentOS/Debian/Ubuntu
- https://shadowsocks.be/9.html

shadowsocks-all.sh
==================
- Auto Install Shadowsocks Server (all version) for CentOS/Debian/Ubuntu
- https://teddysun.com/486.html

haproxy.sh
===============
- Auto Install haproxy for Shadowsocks Server
- https://shadowsocks.be/10.html

Copyright (C) 2014-2019 Teddysun
