# 三个demo体验Python

## 开始编程
命令行输入python开始编程
![](/assets/009.png)

## 初步使用：Hello World
- 输入`print('Hello World!')`按下回车得到结果（打印`Hello World`）,完成。
![](/assets/010.png)
- quit()或exit（）推出python交互式编程环境
![](/assets/011.png)

## 体验特点：分小球
一个常见的面试题，体现Python的精简
req:有10个球分别3红、3蓝、4白，现需要将这10个球放入这3个盒子，要求每个盒子至少有一个白球


```python
import random

```



## 七行代码的后台代码：Flask
Flask是著名的精简型Python Web后台框架，体现其高效
1. 使用pip安装flask模块
- 管理员打开命令行

![](/assets/013.png)
- `python -m pip install --upgrade pip` 升级pip版本
- `pip install flask`安装flask模块
- 编写程序，保存为flask_demo.py（后缀必须为.py）内容如下：


```
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"
    
if __name__ == "__main__":
    app.run()
```


- 在当前目录重开一个命令行（按住shift右键点击程序所在目录窗口的空白处，左键`在此处打开powershell窗口`）
- 输入python falsk_demo.py开启后台服务
![![](/assets/014.png)](/assets/014.png)

- 在浏览器地址栏输入`127.0.0.1:5000`查看效果，实现完成
![](/assets/015.png)


