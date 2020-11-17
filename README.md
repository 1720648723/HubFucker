# HubFucker
开源华科课表软件（[Android下载](https://github.com/Chronostasys/HubFucker/releases))  
<img src="screenshot1.jpg" width="480">
## 功能
纯净的课表  
- 开源
- **不保存、收集**个人隐私。我在此郑重承诺，该应用不会以任何方式收集使用者任何个人信息，不会加入任何商务广告
- 无广告
- 只有一次需要抓取课表，之后可以离线使用
- 启动快速
## 局限性
- 目前仅支持华科的系统。但是未来有计划开放给其它学校系统用的接口
- 抓取课表前，app会模仿普通用户的登录过程给hub系统发送登录请求，以获取session和cookie。在这个过程中，因为hub系统的一个傻逼设计，第一次抓取的速度很慢
- 目前不支持ios，最近也没有支持计划。（没办法，作者一个ios的设备都没有，无法调试，请理解）。明年微软MAUI框架出了之后可以试试做ios

## Build From Source  

请确认下载最新版本的vs2019，并且勾选了.Net跨平台工作负载
然后打开.sln文件，即可编译、运行

## Contribute
我们设计时预留了一些接口，任何人都可以自行实现这些接口
以快速自定义课表的一些功能（比如实现一个其他学校的课表）  
详细信息见[文档](Docs/CONTRIBUTE.md)

## Bug & Feature
关于bug和新功能建议，可以直接通过提交issue来通知我。也欢迎有能力者提交pull request，和我一起让项目变得更好。
## Buy me a cup of tea
想要秋天的第一杯奶茶:)  
<img src="HubFucker/Resources/drawable/pay.jpg" width="480">
