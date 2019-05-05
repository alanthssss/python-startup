# 三个demo体验Python

## 开始编程
命令行输入python开始编程
![](/assets/009.png)

## 初步使用：Hello World
- 输入`print('Hello World!')`按下回车得到结果（打印`Hello World`）,完成。
![](/assets/010.png)
- quit()或exit（）推出python交互式编程环境
![](/assets/011.png)

---
打印Hello World是一门编程语言最朴素的实现。
接下来看第二个demo，用python自带模块和最基础的语法去解决一个面试题，体验其精简，思考其特点。

---

## 精简：五行代码的面试题-分小球
一个常见的面试题，体现Python的精简。
req:有10个球分别3红、3蓝、4白，现需要将这10个球放入这3个盒子，要求每个盒子至少有一个白球。
```python
import random  # 导入random模块
lst = [['w'],['w'],['w'],]
for i in ['w'] + ['r'] * 3 + ['b'] * 3:
    random.choice(lst).append(i)
print(lst)  # 打印结果
```
---
是不是很酷炫呢？
习惯其他语言的程序员看到这里可能为其精简诧异，可能为其担忧，不要紧，深入学习之后就会明白其中的奥秘。
接下来我们看第三个demo,七行代码启动一个web后台，享受python基于强大模块的高效。

---

## 高效：七行代码的后台代码-Flask
Flask是著名的精简型Python Web后台框架，体现其高效。
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


