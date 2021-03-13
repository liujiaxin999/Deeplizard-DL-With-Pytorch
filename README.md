# Neural Network Programming - Deep Learning with PyTorch



## 1 参考资源

中文视频（由UP主**婉yue儿小姐姐**整理）：

> Deeplizard《Pytorch神经网络高效入门教程》中文字幕版
>
> https://www.bilibili.com/video/BV1UE411N7pD?p=33&spm_id_from=pageDriver

官方课程及相关资源：

> Neural Network Programming - Deep Learning with PyTorch
>
> https://deeplizard.com/learn/playlist/PLZbbT5o_s2xrfNyHZsM6ufI0iZENK9xgG 
>
> （国内可以打开，但若要观看每篇文章的视频，则需要科学上网）

代码及知识点整理（由UP主**婉yue儿小姐姐**整理）：

> 总结的DeepLizard的pytorch神经网络编程系列视频的笔记(非官方)
>
> https://github.com/wanyueli/DeepLizard-pytorch-



## 2 说明

### 2.1 关于视频

本菜狗是先看的B站的中文版视频。

由于UP主并没有更新完所有的官方视频，所以，后面几集是去了官方网站去学习。

如果英语过关还是比较推荐去官方学习，博客为辅，视频（也可以显示英文字幕）为主。

### 2.2 关于代码及知识点整理

基于原UP主整理的代码及知识点，我对其进行修改及补充：

- 原UP主的环境没有支持GPU，因此很多GPU相关的则被省略
- 原UP主的视频并没有更新完
- 有些自己在阅读执行的过程中，有疑问的语句，会对其进行注释等



## 3 文件

- .ipynb：总结的视频中会运行的代码及相关知识点笔记
- csv & json文件：保存后续神经网络训练后的结果
- program拆分.png：视频中的一个框架图，原来大部分有耦合的东西可以再次抽象出来形成class或者其他模块
- runs
  - 一系列的文件夹中的文件是不同时间段的模型训练的一些图，用于tensorboard部分学习查看（文件无法识别，无法上传，运行代码可以自动生成）
- resources
  - 原UP主中的，但个人学习并没有用到
- data/FashionMNIST
  - 神经网络模型训练及测试所需要用到的数据集（由于太大，无法上传，运行代码会自动下载）
- README
  - 一些声明等

