# Hackintosh_T1_540S1N

#### 介绍
炫龙（shinelon）炎魔T1 青春版
黑苹果EFI_CLOVER引导文件

#### 安装教程

1.  下载etcher工具，github地址：https://github.com/balena-io/etcher/releases
2.  下载磁盘工具，地址：https://www.diskgenius.cn/download.php
3.  下载dmg镜像，镜像地址：http://mirrors.dtops.cc/iso/MacOS/daliansky_macos/
4.  使用etcher工具将#3下载好的镜像写入准备好的U盘，U盘容量》16G，具体操作https://github.com/balena-io/etcher
5.  使用#2下载好的磁盘工具打开U盘中的ESP盘，替换ESP盘中EFI目录，EFI目录在：10.14（10.15）中。
6.  重启使用U盘方式启动，选中对应镜像安装~~~

#### 使用说明

1. 10.15.7镜像安装过程中会报错：准备安装时发生错误.....无视错误，手动重启，然后选择安装好的盘符继续安装，中间重启重刚刚的步骤,直至提示你无法启动，你手动启动。
2.  三卡（显卡，声卡，网卡）都正常，不正常的课自己下载VoodooHDA：https://github.com/chris1111/VoodooHDA-2.9.2-Clover-V13/releases/tag/V15
3.  有问题请私信qq：987846224

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request
