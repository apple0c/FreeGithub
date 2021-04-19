# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用

## hosts列表
```base
#Github Host Start
github.githubassets.com 185.199.108.154
camo.githubusercontent.com 185.199.108.133
github.map.fastly.net 185.199.108.133
github.global.ssl.fastly.net 199.232.69.194
github.com 140.82.112.3
assets-cdn.github.com 185.199.108.153
api.github.com 140.82.112.6
githubusercontent.com 40.88.122.118
raw.githubusercontent.com 185.199.108.133
documentcloud.github.com 185.199.108.153
gist.github.com 140.82.114.4
training.github.com 185.199.108.153
raw.github.com 185.199.108.133
help.github.com 185.199.108.154
nodeload.github.com 140.82.114.9
status.github.com 140.82.112.17
favicons.githubusercontent.com 185.199.108.133
avatars5.githubusercontent.com 185.199.108.133
avatars4.githubusercontent.com 185.199.108.133
avatars3.githubusercontent.com 185.199.108.133
avatars2.githubusercontent.com 185.199.108.133
avatars1.githubusercontent.com 185.199.108.133
avatars0.githubusercontent.com 185.199.108.133
# Github Host End
```

更新时间：2021-04-19 18:07:24

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder