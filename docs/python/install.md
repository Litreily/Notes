# python3

## install python3

``` bash
sudo apt-get install -y python3-dev build-essential libssl-dev libff i-dev libxml2 libxml2-dev libxslt1-dev zlib1g-dev libcurl4-openssl-d ev
sudo apt-get install -y python3
```

ref: <http://blog.csdn.net/HHTide/article/details/78192314>

## install bs4

如果在系统中只有一个版本的`python3`，可以直接安装

``` bash
sudo apt-get install -y python-bs4
```

如果系统中包含`python2`，`python3`两个版本的话，使用上述指令只会安装用于`python2`的`bs4`，此时可以使用以下方法解决

``` bash
sudo apt-get install -y python3-pip
sudo pip3 install beautifulsoup4
# how to use
>>> from bs4 import BeautifulSoup
```

ref: <https://www.crummy.com/software/BeautifulSoup/bs4/doc/index.zh.html>

## install requests

``` bash
sudo pip3 install requests
# how to use
>>> import requests
```

## install phantomjs

- installl nodejs first

``` js
npm -g install phantomjs-prebuilt
```

## install xpath

``` bash
sudo pip3 install lxml
```

## install pymouse & pykeyboard

``` bash
sudo apt-get install python-xlib
# pip3 install pymouse
sudo pip3 install PyUserInput

# how to use
>>> from pymouse import PyMouse
>>> from pykeyboard import PyKeyboard
>>>
>>> m = PyMouse()
>>> k = PyKeyboard()
```

## install pyinstaller

``` bash
pip3 install pyinstaller
```

``` bash
pyinstall  **.py  # 直接打包
pyinstall -F **.py # 打包成单文件
pyinstall -W **.py # 去掉控制台窗口，黑窗口
pyinstall -i ***.ico **.py # 添加图标 ***
```
