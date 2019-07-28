#  BeryyNice

## 开源的项目汇总

* awsome Projects in github
  * awsome: https://github.com/sindresorhus/awesome    
  * github每日榜单python榜：https://github.com/trending/python?since=daily
* awsome cpp：https://github.com/fffaraz/awesome-cpp#readme
  
* 人工智能

  * pytorch

    * 史上最全的PyTorch学习资源汇总：https://github.com/INTERMT/Awesome-PyTorch-Chinese

      * CV&PyTorch实战

        * [pytorch vision](https://github.com/pytorch/vision)：Torchvision是独立于pytorch的关于图像操作的一些方便工具库。主要包括：vision.datasets 、vision.models、vision.transforms、vision.utils 几个包，安装和使用都非常简单，感兴趣的小伙伴们可以参考以上链接。

        * [OpenFacePytorch](https://github.com/thnkim/OpenFacePytorch)：此github库是OpenFace在Pytorch中的实现，代码要求输入的图像要与原始OpenFace相同的方式对齐和裁剪。

        * [TorchCV](https://github.com/donnyyou/torchcv)：TorchCV是一个基于PyTorch的计算机视觉深度学习框架，支持大部分视觉任务训练和部署，此github库为大多数基于深度学习的CV问题提供源代码，对CV方向感兴趣的小伙伴还在等什么？

        * [Pytorch-cnn-finetune](https://github.com/creafz/pytorch-cnn-finetune)：该github库是利用pytorch对预训练卷积神经网络进行微调，支持的架构和模型包括：ResNet 、DenseNet、Inception v3 、VGG、SqueezeNet 、AlexNet 等。

        * Pt-styletransfer

          ：这个github项目是Pytorch中的神经风格转换，具体有以下几个需要注意的地方：

          - StyleTransferNet作为可由其他脚本导入的类；
          - 支持VGG（这是在PyTorch中提供预训练的VGG模型之前）
          - 可保存用于显示的中间样式和内容目标的功能
          - 可作为图像检查图矩阵的函数
          - 自动样式、内容和产品图像保存
          - 一段时间内损失的Matplotlib图和超参数记录，以跟踪有利的结果

        * [Face-alignment](https://github.com/1adrianb/face-alignment#face-recognition)：Face-alignment是一个用 pytorch 实现的 2D 和 3D 人脸对齐库，使用世界上最准确的面对齐网络从 Python 检测面部地标，能够在2D和3D坐标中检测点。该github库详细的介绍了使用Face-alignment进行人脸对齐的基本流程，欢迎感兴趣的同学学习。

    * PyTorch书籍推荐

      * **《深度学习入门之PyTorch》**，电子工业出版社，作者：廖星宇。这本《深度学习入门之PyTorch》是所有PyTorch书籍中出版的相对较早的一本，作者以自己的小白入门深度学习之路，深入浅出的讲解了PyTorch的语法、原理以及实战等内容，适合新手的入门学习。但不足的是，书中有很多不严谨以及生搬硬套的地方，需要读者好好甄别。 推荐指数：★★★
      * **《PyTorch深度学习》**，人民邮电出版社，作者：王海玲、刘江峰。该书是一本英译书籍，原作者是两位印度的大佬，该书除了PyTorch基本语法、函数外，还涵盖了ResNET、Inception、DenseNet等在内的高级神经网络架构以及它们的应用案例。该书适合数据分析师、数据科学家等相对有一些理论基础和实战经验的读者学习，不太建议作为新手的入门选择。 推荐指数：★★★
      * **《深度学习框架PyTorch入门与实践》**，电子工业出版社，作者：陈云。这是一本2018年上市的PyTorch书籍，包含理论入门和实战项目两大部分，相较于其它同类型书籍，该书案例非常的翔实，包括：Kaggle竞赛中经典项目、GAN生成动漫头像、AI滤镜、RNN写诗、图像描述任务等。理论+实战的内容设置也更适合深度学习入门者和从业者学习。 推荐指数：★★★★
      * **《PyTorch机器学习从入门到实战》**，机械工业出版社，作者：校宝在线、孙琳等。该书同样是一本理论结合实战的Pytorch教程，相较于前一本入门+实战教程，本书的特色在于关于深度学习的理论部分讲的非常详细，后边的实战项目更加的综合。总体而言，本书也是一本适合新手学习的不错的PyTorch入门书籍。 推荐指数：★★★

## C++

https://github.com/fffaraz/awesome-cpp#readme

![awsome project](./pics/awsome.svg)





## 读取二进制文件

ifstream 类进行

文件的打开模式一定要是binary，如果传入不是binary将以ASCII方式打开



# C#

## 什么是c#

简介：

- 面向对象
- 为公共语言基础结构CLI设计
- 广泛接受原因：
  - 面向对象
  - 面向组件
  - 结构化语言
  - 效率高
  - 支持多平台编译
  - .Net框架一部分

特点：

- 构想接近传统的C与C++，面向对象，但是与Java非常相似，有许多强大的编程功能

## C#环境

### .Net 框架 （.Net Framework）

.Net框架可以写出

- windows应用程序
- web应用程序
- web服务

特点：

- 多平台应用程序
  - 适用于c#，C++，VB，Jscript，COBOL等，这些语言可以访问框架，彼此相互交互
- 由一个巨大的代码库组成，用于例如C#这样的客户端语言

### C#的集成开发环境（Integrated Development Environment）

## C#程序结构

结构：

- namespace
  - 定义命名空间
- class
  - 类
- 方法
  - 定义类的行为
- 注释
  - /* */

## C#基本语法

面向对象编程：

- 由各种相互交互的对象组成
- 相同种类的对象有相同类型（在同一class里面）

### 编译与执行c#程序

使用visual studio 编译或者自己编译：

- visual studio
- 保存代码为helloworld.cs
  - csc helloworld.cs



# Logging - 日志记录

思路：使用已有的日志记录库，目前需要一个好用的轻便的

选用templog - A very small and lightweight C++ library to add logging 

## 使用templog

基本想法

- 开发人员讲日志语句插入代码中，用于追踪
- 日志语句中有一些可选参数
  - 用于创建日志消息
  - 日志消息可以发送到程序希望的任意地方

总体概述

- 记录日志

  - 记录器
    - 过滤送入的消息，发送到其他记录器
    - 信息的严重程度和intended audience，被记录器用于筛选信息
    - 这样可以筛选不同等级的消息
      - 就像一棵信息树一样，在底部的是无筛选的全局信息
  - 记录信息策略：
    - 规定哪些消息会被怎样记录
    - templog里面有预置一些记录策略
    - 用户可以自己规定策略
  - 展示信息策略：
    - 信息的格式化展示也是有预置的，也可以通过用户去重新设定
  - 信息的重要等级、受众群体
    - 用于规定信息的等级和分类，展示的信息可以通过这两个参数筛选

- 日志的层次结构和粒度

  - 将一个记录器的日志消息转发到下一个记录器

    - ```c++
      typedef templog::logger<templog::global_logger,templog::sev_warning,templog::audience_list<templog::aud_developer,templog::aud_support>>my_logger;
      ```

    - 如果日志消息具有严重警告性，而且是供开发人员或aud_support使用，则定义my_logger转发到全局记录器templog::global_logger

  - 将信息记录到my_logger里面

    - ```c++
      TEMPLOG_LOG(my_logger,templog::sev_error,templog::aud_support)<<"某些变量的意外值为"<<some_var;
      ```

    - 将一条消息记录为sev_error等级，目标群众为aud_support，由于sev_error高于最低等级sev_warning，且目标群众aud_support位于记录器的受众列表中，因此这条消息会传到global_logger里面，从而根据全局记录器的写入策略，将消息写到任意位置。

## windows 下的grep findstr

使用正则表达式搜索文件中的文本模式

### 语法

```
findstr [/b][/e].........
```

参数

- /b	位于行的开头
- /e    位于行的末尾
- /l     逐字搜索
- /r     使用正则表达式
- /s     在当前目录和所有子目录搜索匹配的文件
- /i     不分大小写
- /x     打印完全匹配的行
- /v     打印不包含匹配的行
- /n     在每个匹配的行前打印行号
- /m    如果文件包含匹配项，则打印文件名
- /o     在每个匹配行之前打印查找偏移量
- /f:File  从指定文件中读取文件列表
- c:String 用指定的文本作为文字搜索字符串

正则表达式



```
D:
cd D:\documents\casitworkspace\Demo-QRCode\Win32\Release
findstr "init Scanner" myeasylog.log

```

# Visual Studio

## 属性配置中使用宏

宏使用的场景：

- 避免重复书写同样性质代码
- 定义常量参数

宏存在的意义：

- 修改某个宏的定义，便修改了所有引用宏的地方所展开的代码

在Visual studio配置c++工程属性的时候，也会遇到这样的场景

- 例如在不同的表单（工程中）填相同的内容（例如某个路径）
- 因此在工程属性配置时也提供了宏这一工具

### C++工程属性中的宏

$(Some Macro)

- 这就是vs中默认定义的一些宏
  - 代表与某个工程相关的常量字符串

# Linux

```
cd D:/documents/编程员/Linux/终端操作
./test.sh a b
```

```
# D:/documents/编程员/Linux/终端操作/test.sh
mycount=0;
while ((mycount<10 )) ; do
	#statements
	echo "hello";
	((mycount=$mycount+1))
done
#
echo "Shell 传递参数示例";
echo "执行的文件名 $0";
echo "第一个参数为 $1";
echo "第二个参数为 $2";
echo "传递的参数以字符串显示 $*";
```

```
#从txt文件中读取数据
#.\test.sh a.txt

if [ $# != 1 ]; then
	echo "Usage: .\test.sh filename"
	exit
fi

if ! [ -f $1 ]; then
	echo "File doesn't exit"
	exit
elif ! [ -r $1 ]; then
	echo "File can't read"
fi
#按下任何键开始进行读取文件操作
read -p "begin to read $1 "

#设置 IFS="\n",去读取每一行
IFS="
"
i=1
for line in `cat $1`
do
	echo $1:$line
	sed -i '/'"$line"'/d' $1 
	let "i=$i+1"
	sleep 0.5s

done

echo "Finished reading file by line "
```



执行某个shell文件

D:/documents/编程员/Linux/终端操作/do.sh

### Shell传递参数

- $1：传递的第一个参数
- $#：传递到脚本的参数的个数
- $*：以一个单字符串显示所有向脚本传递的参数

使用Shell脚本读取文件数据

# Github教程

github是基于git的代码托管平台，付费用户可以建立私人仓库，我们免费用户使用只能使用公共仓库，即代码会公开

- git的版本托管服务

注册账户（已有跳过）

### 创建仓库

安装GitHub，下载地址：http://msysgit.github.io/

#### 配置Git

在本地创建ssh key

```\
ssh-keygen -t rsa -C "506456064@qq.com"
```

打开创建的ssh key文件，复制里面的内容

登录GitHub，添加ssh key

在git bash 下输入

```
ssh -T git@github.com
```

第一次输入，提示是否continue，选yes，就会提示success

#### 把本地仓库上传到github上

第一步：

- 第一次要设置username和email，供每次commit的时候记录
- git config --global user.name "BerryNice"
- git config --global user.email "zhouyixiang@casit.com.cn"

进入要上传的仓库，右键git bash，添加远程地址

如果第一次添加这个仓库

- 要在github上创建一个仓库，例如casitworkspace

- 在git bash里面输入

- ```
  echo "# casitworkspace" >> readme.md
  git init #在这个目录里初始化git仓库
  git add readme.md
  git config --global user.name "BerryNice"
  git config --global user.email "zhouyixiang@casit.com.cn"
  git commit -m "first commit"
  git remote add origin https://github.com/zhouyiixiiang/casitworkspace.git
  git push -u origin master
  ```

在这里我想在github上放一个仓库BerryNice来专门追踪一些优秀的代码，需要在各个电脑上都可以随时浏览

因此

- ```
  echo "# BerryNice" >> readme.md
  git init #在这个目录里初始化git仓库
  git add readme.md
  git commit -m "first commit"
  git remote add berrynice https://github.com/zhouyiixiiang/berrynice.git
  git push -u berrynice master
  ```

### git 相关指令

- git clone
  - 默认：git clone https://github.com/zhouyiixiiang/berrynice.git
    - 会在本地生成一个目录，与远程主机的仓库名同名
  - 如果要不同名，则 git clone https://github.com/zhouyiixiiang/berrynice.git  BerryNice

# 深度学习

CUDA：Compute Unified Device Architecture 统一计算架构，是NVIDIA提出的一种整合技术

- 是NVIDIA对于GPGPU的正式名称
- 使用者可以利用NVIDIA的GeForce8以后的GPU和较新的Quadro GPU进行计算

![CUDA](D:/documents/%E4%B8%AD%E7%A7%91%E9%99%A2/Casit%E6%97%A5%E5%BF%97/pics/Processing%20flow%20on%20CUDA.png)

CUDA Toolkit：CUDA的SDK

- 如果安装了相应版本的显卡驱动，再加上sdk，则可以进行CUDA程序开发
- 需要安装的明细大概包括：
  - 显卡驱动
  - CUDA Toolkit
    - 包括NVCC编译器、CUDA函数头文件、库文件、辅助库（如同FFT等）
  - CUDA Tools SDK（好像和CUDA Toolkit是一个东西，不是必须安装）
    - 用于CUDA分析接口函数
  - GPU 计算SDK代码示例（大量例子源码）
- 安装过程：https://www.jianshu.com/p/ba6beab8ad7f

NVIDIA：（英伟达）发明了GPU

# 机器学习

## dlib

是一个在c++中进行机器学习和数据分析的tookit

覆盖范围：

- 机器学习
- 图像处理
- 数值算法
- 数据压缩

![dlib machine learning](D:/documents/%E4%B8%AD%E7%A7%91%E9%99%A2/Casit%E6%97%A5%E5%BF%97/pics/ml_guide.svg)

特点：

- 文档完善，例子丰富：参考文档