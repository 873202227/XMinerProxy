<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/XMinerProxy/XMinerProxy/main/images/logo.png" width="350"/>
</h1>

<h4 align="center">基于GoLang的高性能多线程ETH/ETC矿池转发中继代理工具</h4>

<p align="center">
  <a href="https://t.me/XMinerProxy">Telegram 讨论群组</a> •
  <a href="https://jq.qq.com/?_wv=1027&k=xo4S29rx">QQ群聊</a>
</p>

![Screenshot](https://raw.githubusercontent.com/XMinerProxy/XMinerProxy/main/images/web_1.png)

## :sparkles: 特性

* :cloud: 矿池转发：支持ETH/ETC的中继代理，支持Stratum/NiceHash/Stratum2所有协议，方便统一管理(其他币种即将更新)
* :zap: 超高性能：采用高效率的GoLang语言编写，并对多线程进行优化
* 💻 自定义抽水：支持中继平台自定义抽水比例进行抽水，并支持在不关闭代理池的情况下进行动态修改
* 📚 多种抽水算法：用户可自选各种抽水算法，防止算力出现周期函数或心跳图的情况
* 💾 安全稳定：支持TCP、SSL等方式，并对CC攻击编写一定的策略进行防护
* :gear: 独家前置代理模式：支持中转服务器到矿池端的加密与混淆，可内网部署
* :outbox_tray: 批量转发：一个软件即可开启对多个矿池的转发，无需开启多个进程
* :card_file_box: 热修改：配置均可网页后台上热修改，无需再修改繁琐配置文件再重启
* :art: 精美后台：后台网页功能全面、折线图、统计丰富
* :eye_speech_bubble: 完善社区支持：Telegram 群组内可帮助处理解决遇到的各类问题，欢迎提出反馈建议
* :rocket: 开箱即用：All-In-One 打包，一键搭建运行，一键配置
* :family_woman_girl_boy: 多系统支持：Windows Linux均可支持使用，无需额外环境等
* :gear: 专业团队：拥有丰富区块链开发的工作经验，多名开发人员来自香港科技大学名校
* :link: 快速响应：可选择开启，伪装低延迟(用户内核延迟处显示的延迟为矿机到中转服务器的延迟)、清理无效提交
* 🌈 ... ...

## :hammer_and_wrench: 部署

最新软件版本请见：<a href="https://github.com/XMinerProxy/XMinerProxy/releases">Github Release</a></br>
Windows 直接下载适用于您目标机器操作系统、CPU架构的主程序，直接运行即可。
</br>
Linux 可按照下述指令运行，请注意下载链接需要适用于您目标机器操作系统、CPU架构。

### Linux一键管理脚本(自带崩溃重启，但无开机自启)
```shell
# 海外伺服器可用
bash <(curl -s -L https://raw.githubusercontent.com/XMinerProxy/XMinerProxy/main/scripts/manage.sh)
# 大陆伺服器可用
bash <(curl -s -L https://cdn.jsdelivr.net/gh/XMinerProxy/XMinerProxy@main/scripts/manage.sh)
```
```shell
# 再次SSH链接可以使用下述指令查看输出
screen -r x_miner_proxy
```

## :scroll: 开发抽水
* 0.3%
