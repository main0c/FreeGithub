# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题

## hosts列表
```base
#Github Host Start
github.githubassets.com 185.199.108.154
camo.githubusercontent.com 199.232.68.133
github.map.fastly.net 199.232.68.133
github.global.ssl.fastly.net 199.232.69.194
github.com 140.82.114.4
api.github.com 140.82.114.6
raw.githubusercontent.com 199.232.68.133
favicons.githubusercontent.com 199.232.28.133
avatars5.githubusercontent.com 199.232.68.133
avatars4.githubusercontent.com 199.232.68.133
avatars3.githubusercontent.com 199.232.68.133
avatars2.githubusercontent.com 199.232.68.133
avatars1.githubusercontent.com 199.232.68.133
avatars0.githubusercontent.com 199.232.68.133
# Github Host End

```

2020-05-31 17:20:58.0708431 +0800 CST m=+20.849945501

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder