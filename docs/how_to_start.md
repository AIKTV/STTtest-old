# STTtest

## 分支规则
### main
为完全保护分支，不允许直接提交，管理员可从develop合并
### develop
半保护分支，不允许直接提交，要求代码提供者审查，管理员审阅，日常使用不直接使用此分支
### 日常使用
请做新内容的时候自行创建新分支，结束时拉取请求至develop

## 环境配置
默认使用Pycharm  
下载使用Pycharm Community版本，*建议版本号2022.3*
</br></br>

### 拉取仓库
默认已经安装git
</br></br>在~~你喜欢的地方~~资源管理器合适的目录（推荐新建Projects），右键选择```git bash here```  
执行命令</br>
```shell
git clone https://github.com/AIKTV/STTtest.git
```
也可使用 [GitHub Desktop](https://desktop.github.com "这是官网页面") clone仓库
</br></br>接下来使用Pycharm打开项目

### 虚拟环境创建
接上
推荐使用Anaconda进行环境管理
默认下载安装完成，教程自己百度
具体方法为
1. 首先打开项目
2. 不要在意可能弹出的Python解释器配置
3. 打开设置-项目-Python解释器-添加本地解释器
4. 选择conda-创建新环境-python版本待定
5. 检查安装完成的python版本与requirements中需求是否一致
</br>使用下方终端，输入
```shell
python --version
```
查看python版本，如果不同，使用
```shell
conda install python=3.x.x
```
改变python版本

### 依赖安装
使用
```shell
pip install -r ../requirements.txt
```
使用镜像
```shell
pip install -r ../requirements.txt -i http://pypi.douban.com/simple/ --trusted-host=pypi.douban.com/simple
```

安装项目所需模块

# 待补充
