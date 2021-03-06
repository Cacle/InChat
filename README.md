# InChat

#### [Developer Chat](https://gitter.im/In-Chat/Lobby)

>The entire MAVEN toolkit is still under construction.... 

**master项目目前在重新构建，运行可能报错，请转到demo分支运行项目。其为原核心项目**

## Summery

***(InChat)Iot Netty Chat***

> 2018-11-15 began to change to MAVEN project package, currently not released, please see the demo branch for details, thank you.

A lightweight, efficient communication framework that supports chat and the Internet of things, you can use it to quickly build a chat server with the background and quickly customize your own communication APIs, including physical networks with different protocols that can be supported.

## Tutorial

* [中文文档说明](doc/document.md)
* [业务场景技术实现分析](doc/work.md)
* [Project design Ideas](doc/design.md)
* [项目设计思路](doc/design_cn.md)

## Learning Resources（欢迎贡献）

* [netty4通信原理](doc/netty-study.md)

## Branch demo

Original Project Core demo, you can first run to understand, imitation WeChat chat application, step by step update, based on Springboot-websocket General framework, combined with Netty to chat social, and record chat logs, asynchronous storage, front-end provisional sui Mobile, add implementation tcp/
IP back-end communication port (MQTT protocol, real-time and single-chip computer and other TCP hardware communication), add picture processing stream, chat implementation text and picture sending function, API call Netty long link execution Send message (number of online, user list)

## Demo Effect Diagram

![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/nettychat/001%20(5).png)
![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/nettychat/001%20(3).png)
![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/nettychat/001%20(4).png)
![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/nettychat/001%20(2).png)
![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/nettychat/001%20(1).png)
![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/nettychat/9.png)
![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/nettychat/10.png)
![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/nettychat/11.png)

## Branch webrtc 

A Netty and web RTC combined to achieve Voice video communication function Branch.

![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/webrtc/TIM%E5%9B%BE%E7%89%8720181121150540.png)

## Branch im-api

Tencent im (cloud communications) backend imitation project, are docked in the form of APIs, if there is a front-end want to dock can run this branch, this branch is expected to end up for a single service concurrent 300,000 users of IM background project

## Branch paho-mqtt

Based on the small program end or mobile Web end of the Paho.js and Java MQTT Client simulation of message subscriptions and communications, small program IoT demo, currently supports WS format

## Branch tcp-wechat

Based on the main communication between the small program end and the single chip computer and other hardware TCP/IP, IoT Center as a relay, this demo will fully implement the specific functions, please see the Branch home page for details

## Download Address

Download Address：https://github.com/UncleCatMySelf/SBToNettyChat/releases

## Issues & Questions

https://github.com/UncleCatMySelf/SBToNettyChat/issues

QQ Group：628793702

## About the author

![Image text](https://raw.githubusercontent.com/UncleCatMySelf/img-myself/master/img/%E5%85%AC%E4%BC%97%E5%8F%B7.png)

