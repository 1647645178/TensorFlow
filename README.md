# TensorFlow
1.首先安装Anaconda3
2.打开anaconda
3.官网安装安装CUDA和CuDNN
4.解压cudnn的压缩包里面有三个文件夹，把这三个文件夹复制到你cuda的安装目录下，地址类似C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0
5.conda create -n tensorflow_gpu python=3.6 #创建环境，也可以使用默认
6.activate tensorflow_gpu #切换环境
7.（5，6可跳过）执行命令 conda install anaconda
8.最后一步：conda install tensorflow-gpu
9.测试gpu是否在运行
