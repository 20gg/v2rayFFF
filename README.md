# v2rayFFF
神秘代码

# Jrohy的一键Trojan面板脚本 （推荐）
## 安装/更新
``source <(curl -sL https://git.io/trojan-install)``

## 卸载
``source <(curl -sL https://git.io/trojan-install) --remove``
## 命令 `trojan` 来管理，不要用443端口


# 网速慢解决 详情：https://v2rayssr.com/teach-vless.html
=============================================================
1. 有域名
2. 注册 Cloudflare 免费内容分发系统
3. X-ui面板安装 `` bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh) ``
4. 输入 x-ui 命令，进入 X-ui 的命令菜单
5. 申请 SSL 证书
6. 套用 CDN 拯救垃圾线路
  1、打开 DNS 解析页面的的 小云朵。
  2、找到 SSL/TLS 选项，把加密选项改为 完全/完全（严格）
  3、在 X-ui 面板建立 VLESS+WS+TLS 的代理节点
7. Cloudflare 优选 IP
