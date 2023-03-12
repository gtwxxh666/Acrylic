---
title: 安装
cover: https://acrylic.leonus.cn/i/2023/02/19/ddz4yq.jpg
tags:
  - Acrylic
  - 主题文档
top_img: https://acrylic.leonus.cn/i/2023/02/19/ddz4yq.jpg
categories: Acrylic
abbrlink: 55021
---
## Git 安裝
在博客根目录里安装稳定版【推荐】

```powershell
git clone -b main https://github.com/hexo-theme-Acrylic/hexo-theme-Acrylic.git themes/Acrylic
```

在博客根目录里安装开发版

```powershell
git clone -b dev https://github.com/hexo-theme-Acrylic/hexo-theme-Acrylic.git themes/Acrylic
```

## npm 安裝

暂未适配

## 应用主题

修改hexo配置文件`_config.yml`，把主题改为`Acrylic`

```yml
theme: Acrylic
```

>如果你没有pug以及stylus的渲染器，请下载安装

```shell
npm install hexo-renderer-pug hexo-renderer-stylus --save
```

## 更好的配置
- macos/linux
在博客根目录运行
```bash
cp -rf ./themes/Acrylic/_config.yml ./_config.Acrylic.yml
```
- windows
复制```/themes/Acrylic/_config.yml```此文件到hexo根目录，并重命名为```_config.Acrylic.yml```

## 报错？你得这样做（必做）
{% link source.zip,source资源,https://download.mengxiangzhicheng.cn/source %}
> 下载后解压后替换掉根目录的source文件夹

## 没梯子无法访问github？没关系，到我们的网盘下载
保证速度，你需要看清声明

{% link 下载站,主题下载,https://download.mengxiangzhicheng.cn %}

下载最新的zip并解压到```theme```目录，之后的就和git clone一样了