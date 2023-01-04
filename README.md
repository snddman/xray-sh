# xray
## 介绍
### install.sh
- xray安装脚本，适用于centos7+/debian9+/ubuntu16.04+
- 调用xray官方安装脚本
- 使用vless+tcp+xtls模式
- 回落使用nginx，配置伪装站

### install_whatever.sh
- xray安装脚本，适用于centos7+/debian9+/ubuntu16.04+
- 调用xray官方安装脚本
- 使用xray回落模式，兼容多种协议(trojan, vless, vmess)
- 最终回落使用nginx，配置伪装站

### install_multi.sh
- xray安装采用指定json目录的形式，功能和install_whatever.sh完全一样

## install.sh使用
```bash
bash <(curl -Ls https://raw.githubusercontent.com/snddman/xray-sh/main/install.sh)
```

## install_whatever.sh使用（稳定版本）
```bash
bash <(curl -Ls https://raw.githubusercontent.com/snddman/xray-sh/main/install_whatever.sh)
```

## install_whatever.sh使用（开发版本）
```bash
bash <(curl -Ls https://raw.githubusercontent.com/snddman/xray-sh/develop/install_whatever.sh)
```

## install_multi.sh使用
```bash
bash <(curl -Ls https://raw.githubusercontent.com/snddman/xray-sh/main/install_multi.sh)
```

## client使用
- OpenWrt
  - [PassWall](https://github.com/xiaorouji/openwrt-passwall)
- Windows
  - [v2rayN](https://github.com/2dust/v2rayN)
- Android
  - [v2rayNG](https://github.com/2dust/v2rayNG)
- iOS / Mac
  - [Shadowrocket](https://apps.apple.com/app/shadowrocket/id932747118)


