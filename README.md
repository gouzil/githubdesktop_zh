# GitHubDesktop_zh

翻译GitHubDesktop为中文

## 注意小版本也不能通用

## 适用版本

2.9.11

## 也可以使用打包好的应用

解压后，直接复制到Applications就可以使用

## 手动替换 

首先下载randerer.js 和 main.js

然后 renderer.js 和main.js 覆盖到这个本地地址就行了

注意:备份自己的renderer.js main.js (替换回来如果还是报错重新安装就行)

```bash
/Applications/GitHub Desktop.app/Contents/Resources/app
```

## 屏蔽更新
修改hosts
```bash
sudo vi /etc/hosts

172.17.0.1 desktop.githubusercontent.com
```

# 本项目已不再更新后续更新将会从源码翻译打包 [here](https://github.com/gouzil/github-desktop-zh)