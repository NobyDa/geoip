## 简介

项目为[Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)的修改版，和原项目有以下不同：

- 中国大陆（CN）IPv4、IPv6地址替换为 [苍狼山庄](https://ispip.clang.cn/)、[纯真IP](https://github.com/metowolf/iplist)、[IPIP.NET](https://github.com/17mon/china_ip_list)、[gaoyifan](https://github.com/gaoyifan/china-operator-ip) 的数据源

- 仅生成 MaxMind mmdb 格式的 GeoIP 数据库（适用于各种代理工具，例如 Surge、Clash）

- 项目每天自动化部署更新
  
  纯自用，如有另外的中国大陆 IP 数据源可提 issues

## 下载

- **仅包含CN**：
  
  | [GitHub](https://raw.githubusercontent.com/NobyDa/geoip/release/Private-GeoIP-CN.mmdb) | [CDN分发](https://cdn.jsdelivr.net/gh/NobyDa/geoip@release/Private-GeoIP-CN.mmdb) |
  | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |

- **完整版**：
  
  | [GitHub](https://raw.githubusercontent.com/NobyDa/geoip/release/Private-GeoIP.mmdb) | [CDN分发](https://cdn.jsdelivr.net/gh/NobyDa/geoip@release/Private-GeoIP.mmdb) |
  | ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |

## License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/) and [GPL-3.0](https://github.com/Loyalsoldier/geoip/blob/master/LICENSE-GPL)

This product includes GeoLite2 data created by MaxMind, available from [MaxMind](http://www.maxmind.com).
