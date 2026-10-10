# WANG888 节点（复制即用 · 不经 Cloudflare）

> 2026-10-10 更新。协议 **VLESS + Reality（直连，不走 Cloudflare）**，v2rayN（电脑）/ v2rayNG（手机）都能用。

## 一、怎么用（三步）

1. 点下面代码块右上角的 **复制** 按钮（或手动全选 → 复制）
2. 打开 v2rayN → 菜单 **服务器** → **从剪贴板导入批量URL**（也可以直接 Ctrl+V）
3. 双击导入进来的节点 → 右键 → **设为活动服务器**

```
vless://318c935d-c195-41d3-99ad-9bbcfdab3386@fl1.balancer.vbuste-bot.com:443?flow=xtls-rprx-vision&encryption=none&security=reality&sni=fl1.balancer.vbuste-bot.com&fp=chrome&pbk=0-or5ogGhYbBgsVSrSC2Fhxyp2BN97Y9pqIdg61Qd08&sid=4be4110078ebed4a&type=tcp&headerType=none#WANG888
vless://86096188-0ece-41af-922d-792c5f96c3ad@201.10.90.118:443?security=reality&encryption=none&pbk=SUqLHKFiu82qz10ruF3RVkoYesyoCcEHCATTz8XPahY&headerType=none&fp=chrome&type=tcp&flow=xtls-rprx-vision&sni=pl1.w-brand.shop&sid=acc1edca2a337172#WANG888-备用
```

## 二、这两条是什么

- **WANG888** —— 芬兰 Helsinki（IP 177.1.188.96）。实测：Google 1.2 秒、LinkedIn 2.2 秒、1MB 下载 2.6 秒（约 400KB/s）。**默认用这条。**
- **WANG888-备用** —— 波兰 Warsaw（IP 45.134.212.101）。约 397KB/s，Google / LinkedIn / GitHub 同样全通。上面那条哪天变慢或连不上，就切这条。

两条都是 vless + Reality 直连节点，**不经过 Cloudflare**（之前 CF Worker 那套在你这条宽带上被整段阻断，所以弃用）。

## 三、注意事项

- 这两条是公共免费节点，**随时可能被回收**。失效了说一声，我按同样的方法（全量抓订阅 → TCP 预筛 → 逐条实测下载速度）重新筛一组换上。
- 速度已经是免费档的上限（约 400KB/s）：刷网页、收发邮件、看 LinkedIn 够用；大文件下载和看视频会吃力。
- 手机端：用桌面上的 **「手机节点-芬兰二维码.png」** 扫码导入（v2rayNG 右上角 + → 扫一扫）。
- 这个仓库设的是 **私有**（只有你自己登录后能看）。如果以后想让 v2rayN 用「订阅地址」自动更新节点，跟我说一声，我把仓库改成公开并给你订阅链接。
