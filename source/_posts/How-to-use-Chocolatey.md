---
title: How to use Chocolatey
date: 2022-02-23 00:30:17
tags: 技术教学
---
# Chocolatey使用说明

## 1.安装软件
>choco install 软件的包名称  

回车，软件的包名称和软件名称可能不一样，推荐直接去官方的软件列表搜到名字之后再用。 
## 2.安装Chocolatey的图形界面
>choco install chocolateygui

## 3.卸载软件
>choco uninstall 软件的包名称
## 4.更新所有软件
>choco upgrade all

---

##补充
查看本地安装的所有应用

>choco list/search -l 
搜索应用

>choco list/search 应用名 
搜索应用（精准匹配）

>choco list/search 应用名 -e 
只返回id中含有关键字的应用

>choco list/search 应用名 --by-id-only 
自动安装应用（一个或多个）

>choco install 应用名 应用名 应用名 
安装指定版本的应用

>choco install 应用名 --version 版本号 
自动安装应用并确认所有提示（一个或多个）

>choco install 应用名 -y 
自动卸载应用（一个或多个）

>choco upgrade 应用名 应用名 应用名 
自动更新应用（一个或多个）

>choco uninstall 应用名 应用名 应用名 