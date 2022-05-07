# Auto Reconnect Campus Network (自动重连校园网)

## requirements

```bash
pip install -r requirements.txt
```

## 使用方法

~~从[chromedriver](http://chromedriver.storage.googleapis.com/index.html)下载并解压得到`chromedriver.exe`，将其放在主程序同一文件夹下。~~

1. 方法一: PYTHON

```bash
python connconnect_campus_network.py --uid [用户名] --pwd [密码]
```

2. 方法二: EXE

由pyinstaller打包获得:

```bash
pyinstaller -F connconnect_campus_network.py
```

或者直接下载打包好的[connconnect_campus_network.exe](https://github.com/kanchenhao/auto-reconnet-campus-network/releases/tag/v0.0.2)~~至chromedriver.exe同一文件夹下~~.

双击或者在cmd中运行如下命令:

```bash
connconnect_campus_network.exe --uid [用户名] --pwd [密码]
```
