# Linux进程防火墙

#### 一 、介绍
Linux进程防火墙主要用途是发现和防御服务器高级隐藏木马通信、违规外联、数据泄露等，让服务器流量可视化。

#### 二、承诺和不承诺
承诺：为了保证服务器安全，除首次安装，任何时候绝不联网。

不承诺：无论任何原因引发的任何问题，都不负任何责任；请务必在测试环境完美演练后，再部署到生产环境。

注意：WEB管理9998端口禁止向公网开放，或者严格设置IP白名单访问权限。

#### 三 主要功能
    1、全程记录每个进程的通信IP、进出流量、在线时长等。。
    2、全程记录各进程的原始流量，保存为pcap格式，发现特别隐蔽的内存木马等。
    3、用AI技术分析检测异地IP、异常进程、危险木马、违规外IP外联通信等，保障进程安全。

#### 四、安装步骤
支持Linux x86 64位系统（arm暂不开放），保证可以上网，以root权限运行下面命令：

    1、 wget http://101.42.31.94/openhfw
    2、 chmod +x ./openhfw
    3、 ./openhfw

首次安装下载大约半分钟，出现System is running.....代表安装成功，可以WEB管理口9998（防火墙允许）登录进去。

#### 五、运行停止卸载
启动运行:  ./openhfw         后台模式运行:   ./openhfw daemon

停止运行:  ./openhfw stop    卸载 :   rm  /openhfw/ -rf

默认没加开机启动，请自行把openhfw 加入开机启动程序。

#### 六、实战演示地址

实战地址 [http://39.106.251.213/hiproc.html](http://101.42.31.94/hiproc.html)

#### 七、付费演示地址

请用大屏电脑观看，首次加载大屏组件需要10秒：
集中管控大屏 [http://39.106.251.213/center.html](http://101.42.31.94/center.html)

#### 八、源码或技术白皮书请加微信号httpwaf

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/wechat.png)

#### 九、来一张首页图片

![](https://gitee.com/httpwaf/httpwaf/raw/master/img/home.png)
