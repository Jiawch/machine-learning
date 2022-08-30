# machine-learning

## RNN, LSTM

- [RNN](https://zhuanlan.zhihu.com/p/28919765)

## TTS

- [TTS](https://zhuanlan.zhihu.com/p/45517433)

## Mixture Density Network

- [MDN](https://zhuanlan.zhihu.com/p/37992239), 可以用来处理多值函数

## Domain adaptation

- [Domain-Adversarial Training](https://zhuanlan.zhihu.com/p/51499968)

## SI-SDR，SI-SNR Loss

- [si-sdr](https://github.com/pfnet-research/meta-tasnet/blob/30eba9663445226f5de251297007b94e4f3b1ebc/utility/loss.py#L5)

## 语音数据增强算法汇总（附代码）

- [语音数据增强算法汇总](https://blog.csdn.net/qq_36999834/article/details/109851965)
- [github](https://github.com/zzpDapeng/speech_data_augment)
- [语音的buzzy noise](https://github.com/mmorise/World/issues/44)
- [语音相关期刊,会议](https://blog.csdn.net/zongza/article/details/82924070?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param)

## 唱歌相关

- [midi 音符对应表](https://blog.csdn.net/claroja/article/details/104247327?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param)
- [音高-频率](https://bideyuanli.com/声乐基础理论/音高)
- [midi 2 hz](https://forum.pdpatchrepo.info/topic/4090/midi-to-hz-and-hz-to-midi-formulas)
- [Hz 和 音分cent 关系](http://www.tunersnote.com/30001259762338335469356723889924459.html)，一个半音=100cent

# SCI, ccf

- [最新人工智能领域SCI期刊查询及投稿分析系统](https://www.letpub.com.cn/index.php?page=journalapp&view=researchfield&fieldtag=251&firstletter=&currentpage=1#journallisttable)
- [ccf rank](https://www.ccf.org.cn/Academic_Evaluation/AI/)
- [国内外学术期刊常识大科普](https://mp.weixin.qq.com/s?__biz=MzU1Mjk0NjIzMw==&mid=2247484412&idx=1&sn=dd439058f23e1312234424b753effec6&scene=19#wechat_redirect)

# Latex

- [LaTeX公式编辑器](https://www.latexlive.com/##)
- [LaTeX图片位置固定](https://blog.csdn.net/zhuang19951231/article/details/79176298)
- [LaTeX 各种命令，符号](https://www.cnblogs.com/bnuvincent/p/9550350.html)
- [PDF 裁剪（在线）](https://deftpdf.com/zh/crop-pdf)

# 雅思

- [剑桥](http://top.zhan.com/ielts/read/review-185-0-1-3998746.html)

# 李宏毅

- [DL](http://speech.ee.ntu.edu.tw/~tlkagk/courses_DLHLP20.html)
- [ML](http://speech.ee.ntu.edu.tw/~tlkagk/courses_ML19.html)

# librosa

- [函数快览](https://learnku.com/articles/45084)
- [作图](https://zhuanlan.zhihu.com/p/198900624)

# MFA

- [汉语（普通话）的音素对齐](https://www.bilibili.com/read/cv6815691/)
- [short version](http://www.cs.columbia.edu/~ecooper/tts/mfa.html)
- [version 1.0.1](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner/releases/tag/v1.0.1)

# WORLD

- [语音合成系统之WORLD简介](https://zhuanlan.zhihu.com/p/76704615)

# RNN-T

[RNN-T pytorch 绑定](https://github.com/awni/transducer)  
[espnet 要安装的 transducer ](https://github.com/HawkAaron/warp-transducer)  
[基于 RNN Transducer 的 音素识别](https://github.com/HawkAaron/RNN-Transducer)


# torch.autograd.Function

- [自动梯度](https://blog.csdn.net/tsq292978891/article/details/79364140)

# Few Shot

-[原理](https://www.zmonster.me/2019/12/08/few-shot-learning.html)

# MAS， 维特比算法

- [MAS](https://blog.csdn.net/weixin_42262721/article/details/110457491)
- [维特比算法](https://www.zhihu.com/question/20136144/answer/763021768)

# Parallel tacotron 2

- [learnable upsample layer](https://zhuanlan.zhihu.com/p/388926701)

————————————————————————————————
# DL/ML 基础

## 优化器
> 从均值方差的角度思考
- [SGD](https://www.cnblogs.com/guoyaohua/p/8542554.html)
- [Momentum, RMSprop, Adam](https://zhuanlan.zhihu.com/p/43438597)

## 交叉熵损失vs.平方损失
- [梯度](https://blog.csdn.net/efei7968/article/details/88724712)
- MSE可能引导sigmoid/Softmax进入梯度平缓层，而对于交叉熵损失的求导与激活函数的导数无关。

## 方差和偏差
- [过拟合和欠拟合]
- [强模型和弱模型]
  - [bagging](https://cloud.tencent.com/developer/news/393218)
  的基模型为强模型，最后投票决定（权值相同），并联训练；
  （当强模型为决策树，则 bagging 进化为随即森林）
  - [boosting](https://blog.csdn.net/whiteinblue/article/details/14518773)
  的基模型为弱模型，最后投票决定（权值不同），串联训练
  （核心思想为根据上一次的分类结果，加权采样训练样本，训练下一个弱分类器，最后投票的时候，分类器中准确率高的被赋予较高的权重）

## 为什么使用 SGD 不用 BGD
- BGD 迭代慢
- SGD 引入随机性，即使陷入局部最小，也有机会跳出来

## [初始化](https://zhuanlan.zhihu.com/p/133835463)
- pretrain
- 随机初始化
  - 高斯
  - 均匀
- 特别(如果一个神经元输入很多，则每个输入连接上的权重就应该小一些，以免输出过大，使得输入输入输出方差保持一致)
  - Xavier
  - Kaiming
  
![](https://pic3.zhimg.com/80/v2-6302a7093b93e1376e54e95033c58086_1440w.jpg)

## 音频格式转换
- [批量修改wav文件的采样率](https://blog.csdn.net/chenxieyy/article/details/51506766)
- [批量转换32bit wav为16bit](https://blog.csdn.net/zmlovelx/article/details/80263018)
