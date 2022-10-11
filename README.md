

Installation
------------
windows安装pyspider
---
1、使用conda创建pyspider环境,激活pys环境
```
conda create -n pys python=3.6
activate pys
```
2、windows安装pycurl有问题,单独下载pycurl-7.43.0.4-cp36-cp36m-win_amd64.whl安装
```
pip install pycurl-7.43.0.4-cp36-cp36m-win_amd64.whl
```
3、下载源码，从源码安装pyspider
```
git clone --depth=1 https://github.com/sunjxf/pyspider.git
cd pyspider
python setup.py install
```
4、运行, 浏览器访问 [http://localhost:5000/](http://localhost:5000/)
```
pyspider
```
