![在这里插入图片描述](https://img-blog.csdnimg.cn/06cacf039b02485fb2b2b34015f7ab6d.jpeg#pic_center)

---
# 前言

+ 👑 本专栏适用人群：🚨🚨🚨`深度学习初学者`，`刚刚接触时间序列的用户群体`，专栏将具体讲解如何快速搭建深度学习模型用自己的数据集实现时间序列预测，`快速让新手小白能够对基于深度学习方法进行时间序列预测有个基本的框架认识`。

+ 👑 本专栏整理了`《深度学习时间序列预测案例》`，内包含了各种不同的基于深度学习模型的时间序列预测方法，例如`LSTM、GRU、CNN（一维卷积、二维卷积）、LSTM-CNN、BiLSTM、Self-Attention、LSTM-Attention、Transformer等经典模型`，💥💥💥包含项目原理以及源码，每一个项目实例都附带有`完整的代码+数据集`。

![在这里插入图片描述](https://img-blog.csdnimg.cn/34ba34a13fbc4136b4b69fdd0836292b.png#pic_center)


正在更新中~ ✨  

![在这里插入图片描述](https://img-blog.csdnimg.cn/img_convert/e0fb91ed8ee12ea1d35b3a0339ff9282.jpeg#pic_center)



🚨 我的项目环境：

+ 平台：Windows10
+ 语言环境：python3.7
+ 编译器：PyCharm
+ PyTorch版本：1.11.0

---

# 🌠 『精品学习专栏导航帖』

+ **🐧[<font color=Tomato>【Matplotlib绘制图像目录】Python数据可视化之美](https://weibaohang.blog.csdn.net/article/details/128132121)🐧**

+ **🎠[<font color=Sienna>【Pandas数据处理100例目录】Python数据分析玩转Excel表格数据](https://weibaohang.blog.csdn.net/article/details/128067702)🎠**

+ **🐳[<font color=red>最适合入门的100个深度学习实战项目](https://weibaohang.blog.csdn.net/article/details/127365867?spm=1001.2014.3001.5502)🐳**
+ **🐙[<font color=orange>【PyTorch深度学习项目实战100例目录】项目详解 + 数据集 + 完整源码](https://weibaohang.blog.csdn.net/article/details/127128637?spm=1001.2014.3001.5502)🐙**
+ **🐶[<font color=gold>【机器学习入门项目10例目录】项目详解 + 数据集 + 完整源码](https://blog.csdn.net/m0_47256162/article/details/128011714?spm=1001.2014.3001.5501)🐶**
+ **🦜[<font color=green>【机器学习项目实战10例目录】项目详解 + 数据集 + 完整源码](https://blog.csdn.net/m0_47256162/article/details/128055406?spm=1001.2014.3001.5501)🦜**
+ **🐌[<font color=darkcyan>Java经典编程100例](https://blog.csdn.net/m0_47256162/article/details/113728127)🐌**
+ **🦋[<font color=blue>Python经典编程100例](https://blog.csdn.net/m0_47256162/article/details/110746376)🦋**
+ **🦄[<font color=purple>蓝桥杯历届真题题目+解析+代码+答案](https://blog.csdn.net/m0_47256162/article/details/110476937)🦄**
+ **🐯[<font color=deepskyblue>【2023王道数据结构目录】课后算法设计题C、C++代码实现完整版大全](https://weibaohang.blog.csdn.net/article/details/124415748)🐯**

---
+ **✨[<font color=#ff99> 试读文章：GRU实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128595011)✨**

---

![在这里插入图片描述](https://img-blog.csdnimg.cn/ea17c7ac796b40148efd16596b42a449.png#pic_center)
### 🌈『目录』
**📢 数据集介绍**

+ [（一）：深度学习时间序列预测项目案例数据集介绍](https://weibaohang.blog.csdn.net/article/details/128585962)
---
**📢 RNN篇**
+ [（一）：GRU实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128595011)
+ [（二）：LSTM实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128605806)
+ [（三）：RNN实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128619443)
+ [（四）：BiLSTM(双向LSTM)实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128622372)
---
**📢 CNN篇**
+ [（一）：CNN(一维卷积Conv1D)实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128666467)
+ [（二）：CNN(二维卷积Conv2D)实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128670832)
---
**📢 模型融合篇**
+ [（一）：LSTM+CNN实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128678028)
+ [（二）：LSTM+注意力机制(Attention)实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128697592)
+ [（三）：CNN+注意力机制(Attention)实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128720057)
+ [（四）：CNN+LSTM+Attention实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128720482)
---
**📢 MLP篇**
+ [（一）：MLP(ANN)实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128650857)
---
**📢 注意力篇**
+ [（一）：注意力机制(Attention)实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128689947)
---
**📢 时间卷积网络篇**
+ [（一）：TCN(时间卷积网络)实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/129443456)
---
**📢 其它模型篇**
+ [（一）：Transformer实现时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128743298)
---
**📢 注意信息**
+ [（一）：时间序列数据预测结果为一条直线原因总结](https://weibaohang.blog.csdn.net/article/details/128720691)
---
**📢 单变量、多变量篇**
+ [（一）：LSTM实现单变量时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128605806)
+ [（二）：LSTM实现多变量时间序列预测(PyTorch版)](https://weibaohang.blog.csdn.net/article/details/128753861)
---
**📢 多步预测篇**
+ [（一）：时间序列多步预测经典方法总结](https://weibaohang.blog.csdn.net/article/details/128754086)
+ [（二）：LSTM实现多变量输入多步预测时间序列预测(PyTorch版) —— 直接多输出](https://weibaohang.blog.csdn.net/article/details/128756380)
+ [（三）：LSTM实现多变量输入多步预测时间序列预测(PyTorch版) —— 递归多步预测（单步滚动预测）](https://weibaohang.blog.csdn.net/article/details/128762374)
+ [（四）：LSTM实现多变量输入多步预测时间序列预测(PyTorch版) —— 直接多步预测（多模型单步预测）](https://weibaohang.blog.csdn.net/article/details/128758197)
+ [（五）：LSTM实现多变量输入多步预测时间序列预测(PyTorch版) —— 直接递归混合预测（多模型滚动预测）](https://weibaohang.blog.csdn.net/article/details/128762937)
+ [（六）：LSTM实现多变量输入多步预测时间序列预测(PyTorch版) —— Seq2Seq多步预测](https://weibaohang.blog.csdn.net/article/details/128760606)
