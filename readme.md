# Adlist
Adlist是DNSmasq屏蔽广告的规则文件，包含常见网站广告规则，不断收集整理中，欢迎帮助完善。

### 使用方法
* 参考：[Linux安装DNSmasq搭建自己的公共DNS](https://www.xiaoz.me/archives/8303)安装DNSmasq
* 下载规则：
```bash
cd /etc/dnsmasq.d
wget https://raw.githubusercontent.com/helloxz/adlist/master/adblock.conf
service dnsmasq restart
```