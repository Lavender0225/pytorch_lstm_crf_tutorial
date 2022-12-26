# Tutorial: Pytorch of LSTM and CRF Model

这是一篇如何实现Pytorch版本的LSTM-CRF模型的教程。

所用代码来自 [Pytorch Toturial](https://pytorch.org/tutorials/beginner/nlp/advanced_tutorial.html) 。关于这篇教程的更详细的文章请看我的知乎专栏文章[一文搞懂LSTM CRF模型](https://zhuanlan.zhihu.com/p/594543744/preview?comment=0&catalog=0)。

## 环境准备

1. 新建conda隔离环境
   
   - 安装Anaconda3
   
   - `conda create -n torch python==3.7`
   
   - 进入新环境 `conda activate torch`

2. 在pytorch官网选择和自己服务器等条件匹配的安装命令进行pytorch安装
   
   - https://pytorch.org/get-started/locally/
     3- 安装jupyter notebook
   
   - `conda install jupyter notebook`

## 运行

将本仓库clone至本地：

`git clone https://github.com/Lavender0225/pytorch_lstm_crf_tutorial.git`

启动jupyter notebook

`jupyter notebook`

在打开的notebook web操作界面中打开bilstm_crf_pytorch，就可以啦~~

Enjoy your study !
