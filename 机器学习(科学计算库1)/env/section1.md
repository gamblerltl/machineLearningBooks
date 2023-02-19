# 2.1 库的安装

## 学习目标

- 目标
  - 搭建好机器学习基础阶段的环境

---

整个机器学习基础阶段会用到Matplotlib、Numpy、Pandas等库，为了统一版本号在环境中使用，将所有的库及其版本放到了文件requirements.txt当中，然后统一安装

**新建一个用于人工智能环境的虚拟环境**

```
mkvirtualenv ai
```

```python
matplotlib==2.2.2
numpy==1.14.2
pandas==0.20.3
tables==3.4.2
jupyter==1.0.0
```
注意：

- 每个包安装的过程中，尽量指定稳定版本进行安装

使用pip命令安装

```
pip3 install -r requirements.txt
```



## 小结

- 机器学习(科学计算库)阶段环境的搭建和基本库的安装
  - 注意：最好安装指定的稳定版本

