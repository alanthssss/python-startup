# 环境搭建（编程前的准备）
---
说明：
- mac自带Python2，可以无差别实现下一章的三个demo（自行安装pip或用其他方法安装flask模块即可），配置Python3开发环境、使用Python都很简单，下面给出安装包链接，在此不做详细介绍。
- 在windows配置Python开发环境有两种方法比下文介绍的朴素方法快的多：linux子系统、Docker。此处只提出方法名，没有使用经验的话就按照下面的方法开始吧。


## 安装包下载

全部需要的文件
Python安装包(根据系统选择链接下载当前最新Python3安装包)
- [windows x64](https://www.python.org/ftp/python/3.7.3/python-3.7.3-amd64.exe) 
- [mac x64](https://www.python.org/ftp/python/3.7.3/python-3.7.3-macosx10.9.pkg)
   
## 安装
1. Python(除CentOS系统外只说关键点)
    - windows勾选将Python3相关目录添加至环境变量
- Pycharm（百度lanyu打开第一个链接有你要的一切）

### windows安装Python3
此处会安装好Python3以及包管理工具pip

1.选择windows需要的安装包点击开始安装
![](/assets/000.png)
2.  自动配置环境变量，以及选择自己配置安装（主要为了能让本机所有用户使用此次安装的Python）
![](/assets/001.png)
3. 进入下一步，再点击Next（pip为Python的模块管理工具）
![![](/assets/002.png)](/assets/002.png)
4. 勾选为所有用户安装，安装位置发生改变，初步配置完成，点击Install

- 勾选前

![](/assets/003.png)

- 勾选后

![](/assets/004.png)
- 安装中

![](/assets/005.png)
- 安装完成

![](/assets/006.png)
5. 验证安装
- `win+r`打开`运行`，输入`cmd`，按`enter（回车）`打开`命令行`

![](/assets/007.png)

- 输入`python -V`、`pip -V`（注意大写V）得到python版本、pip版本，安装完成

![](/assets/008.png)




