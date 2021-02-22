# Clash For Magisk

## 使用方法

1. 使用Magisk Manager安装模块,在安装时将自动下载[Geoip](https://github.com/Hackl0us/GeoIP2-CN)文件、[Yet Another Clash Dashboard](https://github.com/haishanh/yacd)和安装最新稳定版[Clash](https://github.com/Dreamacro/clash)内核.
2. 确保clash的配置文件中有`tproxy-port`和`dns`段的配置,可以参考[example.yaml](./example.yaml)
文件中相应字段.
3. 把clash配置文件移动到`/data/clash`目录下,重启手机,开机后clash配置无问题后将会自动开启.
4. 使用Magisk Manager禁用或开启Clash For Magisk模块可使clash服务停止或启动且不需要重启手机.
