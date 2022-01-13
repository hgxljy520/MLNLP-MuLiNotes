<p align="center">
<h1 align="center"> <img src="./imgs/icon/ai.png" width="30" />《动手学习深度学习》</h1>
</p>

[项目动机](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/README.md#项目动机),[课程简介](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/README.md#课程简介), [课程资源](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/README.md#课程资源), [教材目录](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/README.md#课程目录), [笔记](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/README.md#笔记), [文件夹说明](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/README.md#文件夹说明), [组织者](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/README.md#组织者), [贡献者](https://github.com/MLNLP-World/DeepLearning-MuLi-Notes/blob/main/README.md#贡献者)


---

## 项目动机

《动手学习深度学习》是**李沐老师**（AWS 资深首席科学家，美国卡内基梅隆大学计算机系博士）主讲的一系列深度学习视频。本项目收集了我们在寒假期间学习《动手学习深度学习》过程中详细的**markdown笔记**和相关的**jupyter代码**。赠人玫瑰，手留余香，我们将所有的**markdown**笔记开源，希望在自己学习的同时，也对大家学习掌握李沐老师的《动手学习深度学习》有所帮助。

>本项目的特色：
>1. **markdown笔记**与原课程视频一一对应，可以帮助大家一边听课一边理解。
>2. **jupyter代码**均有详细中文注释，帮助大家更快上手实践。



课程视频**共73节**，单个视频平均时长**不超过30分钟**，预计**寒假40天**内可以学习完毕。

## 课程简介


通常我们提到深度学习，常常会忘记深度学习只是机器学习的一小部分，而认为它是独立于机器学习的单独模块。这是因为机器学习作为一门历史更悠久的学科，在深度学习没有问世之前，在现实世界的应用范围很窄。在语音识别、计算机视觉、自然语言处理等领域，由于需要大量的领域知识并且现实情况异常复杂，机器学习往往只是解决这些领域问题方案中的一小部分。但是就在过去的几年里，深度学习的问世和应用给世界带来了惊喜，推动了计算机视觉、自然语言处理、自动语音识别、强化学习和统计建模等领域的快速发展，并逐渐引领潮流，在世界掀起了一波人工智能的革命。

在 **《动手学习深度学习》** 课程中，既有少量的机器学习的基础知识，比如：__线性神经网络，多层感知机__ 等等；又有如今前沿应用的 __各种深度学习模型：包括leNet，ResNet，LSTM，BERT……__ 同时每一章节的讲解还配备由pytorch实现的代码、教科书等等，可以帮助同学在短期内掌握深度学习的基础模型与前沿知识和并提高实践能力。

## 课程资源

- B站教学网址：[动手学习深度学习（已完结）](https://space.bilibili.com/1567748478/channel/seriesdetail?sid=358497)
- 教材网址：[《动手学深度学习》(中文版)](https://zh-v2.d2l.ai), [《Dive into Deep Learning》 0.17.1 documentation](https://d2l.ai)
- 课程主页：[https://courses.d2l.ai/zh-v2/](https://courses.d2l.ai/zh-v2/)
- 论坛网址：[discuss.d2l.ai](https://discuss.d2l.ai/c/chinese-version/16)，[discuss.pytorch](https://discuss.pytorch.org)

此外，本门课程还有相应的代码实现。**每章都有相应的jupyter记事本，提供模型的完整python代码**，所有的资源都可在网上免费获取。


## 教材目录

[《动手学深度学习》(中文版)](https://zh-v2.d2l.ai)和英文版[Dive into Deep Learning 0.17.1 documentation](https://d2l.ai)教材目录及章节链接如下：


| 章节 | 中文版                                                       | 英文版                                                       |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | [前言](https://zh-v2.d2l.ai/chapter_introduction/index.html) | [Introduction]((https://d2l.ai/chapter_introduction/index.html)) |
| 2    | [预备知识](https://zh-v2.d2l.ai/chapter_preliminaries/index.html) | [Preliminaries](https://d2l.ai/chapter_preliminaries/index.html) |
| 3    | [线性神经网络](https://zh-v2.d2l.ai/chapter_linear-networks/index.html) | [Linear Neural Networks](https://d2l.ai/chapter_linear-networks/index.html) |
| 4    | [多层感知机](https://zh-v2.d2l.ai/chapter_multilayer-perceptrons/index.html) | [Multilayer Perceptrons](https://d2l.ai/chapter_multilayer-perceptrons/index.html) |
| 5    | [深度学习计算](https://zh-v2.d2l.ai/chapter_deep-learning-computation/index.html) | [Deep Learning Computation](https://d2l.ai/chapter_deep-learning-computation/index.html) |
| 6    | [卷积神经网络](https://zh-v2.d2l.ai/chapter_convolutional-neural-networks/index.html) | [Convolutional Neural Networks](https://d2l.ai/chapter_convolutional-neural-networks/index.html) |
| 7    | [现代卷积神经网络](https://zh-v2.d2l.ai/chapter_convolutional-modern/index.html) | [Modern Convolutional Neural Networks](https://d2l.ai/chapter_convolutional-modern/index.html) |
| 8    | [循环神经网络](https://zh-v2.d2l.ai/chapter_recurrent-neural-networks/index.html) | [Recurrent Neural Networks](https://d2l.ai/chapter_recurrent-neural-networks/index.html) |
| 9    | [现代循环神经网络](https://zh-v2.d2l.ai/chapter_recurrent-modern/index.html) | [Modern Recurrent Neural Networks](https://d2l.ai/chapter_recurrent-modern/index.html) |
| 10   | [注意力机制](https://zh-v2.d2l.ai/chapter_attention-mechanisms/index.html) | [Attention Mechanisms](https://d2l.ai/chapter_attention-mechanisms/index.html) |
| 11   | [优化算法](https://zh-v2.d2l.ai/chapter_optimization/index.html) | [Optimization Algorithms](https://d2l.ai/chapter_optimization/index.html) |
| 12   | [计算性能](https://zh-v2.d2l.ai/chapter_computational-performance/index.html) | [Computational Performance](https://d2l.ai/chapter_computational-performance/index.html) |
| 13   | [计算机视觉](https://zh-v2.d2l.ai/chapter_computer-vision/index.html) | [Computer Vision](https://d2l.ai/chapter_computer-vision/index.html) |
| 14   | [自然语言处理：预训练](https://zh-v2.d2l.ai/chapter_natural-language-processing-pretraining/index.html) | [Natural Language Processing: Pretraining](https://d2l.ai/chapter_natural-language-processing-pretraining/index.html) |
| 15   | [自然语言处理：应用](https://zh-v2.d2l.ai/chapter_natural-language-processing-applications/index.html) | [Natural Language Processing Applications](https://d2l.ai/chapter_natural-language-processing-applications/index.html) |
| 16   | 推荐系统                                                     | [Recommender Systems](https://d2l.ai/chapter_recommender-systems/index.html) |
| 17   | 生成对抗网络                                                 | [Generative Adversarial Networks](https://d2l.ai/chapter_generative-adversarial-networks/index.html) |
| 18   | 附录： 深度学习中的数学基础                                               | [Appendix: Mathematics for Deep Learning](https://d2l.ai/chapter_appendix-mathematics-for-deep-learning/index.html) |
| 19   | [附录： 深度学习工具](https://zh-v2.d2l.ai/chapter_appendix-tools-for-deep-learning/index.html) | [Appendix: Tools for Deep Learning](https://d2l.ai/chapter_appendix-tools-for-deep-learning/index.html) |