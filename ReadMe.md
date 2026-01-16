# EInstall 1.0 
* 简单及用
* 快速上手
* 语法简单
---
## 目录
[1.简单介绍](#简单介绍)
[2.安装包配置语法](#安装包配置语法)

---

## 简单介绍
EInstall 1.0 
由LaoDay(SYSTEM-XJ380-OS)在 2026/1/15 编写
###### 励志为人民们编写比 NSIS 还要
> * 小巧
> * 优雅
> * 语法简单
的安装程式
### LaoDay 听到了人民的声音!
(其实就是 LaoDay 觉得用NSIS太麻烦了)

## 安装包配置语法
这里拿默认的举例子
```ini
[EInstall]
SetSetupAppVersion=1.0.0

[Base]
SetMainNameTable=测试程式
SetSetupApp=C:\Test
SetMainAppFileName=1
SetMainAppFile=exe
```
是不是很头疼啊🤣
```ini
;版本信息（不小心把版本放到了 Einstall 里🤣）
[EInstall]
;版本
SetSetupAppVersion=1.0.0

;顾名思义
[Base]
;程式名
SetMainNameTable=测试程式
;默认释放目录
SetSetupApp=C:\Test
;下面的 1.0 用不上
;我还是讲讲吧
;主程序名
SetMainAppFileName=1
;主程序类型
SetMainAppFile=exe
```
简单多了是不是😁
###### 1.0 我还没加下面的呢
```ini
[1.0没加的配置项]
;是否成为在线安装程式
SetIfOnlineSetup=false
;在线安装程式下载Url
SetOnlineSetupDownloadUrl=https://system-xj380-os.github.io/aaa/aaa.zip
;是否在安装结束后运行脚本（添加到程式注册项）
SetIfDoneRunBat=false
;脚本名称
SetDoneRunBatName=Base

```
HAHAHA


