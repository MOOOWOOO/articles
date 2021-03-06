# 双拼入门教程

2016年过半，到目前为止，我个人认为习得的**最值得推荐的技能之一**就是双拼，奈何向周围的朋友推荐却普遍反映根本看不懂网上的教学说明。所以记录此文，将我浅薄的学习双拼的经验分享给大家。

## 历史

一开始我们还是先了解一下双拼本身。目前常见的汉字输入系统主要有`全拼`、`五笔`和`双拼`。全拼因其简单直接所以使用人群最广，五笔因早推广和其定位生僻字的能力积累了大批拥趸。而双拼自发明之日起就感觉不温不火，始终流传于小圈子内。许多新手接触后觉得双拼似乎包含了全拼和五笔的缺点，既要记键位，又得会拼音，唯一被粉丝们夸耀的好像也只有极高的输入效率。但上手如此困难，哪有效率可言呢？

的确，“过高”的入门门槛似乎让双拼成为如同鸡肋一般的存在，但我以自己的亲身经历保证，双拼绝不是大家想象的这般无用。一起问题，都源于双拼没有一个很好的入门教程。今天我就来搞个新闻，做一点微小的贡献。

## 简介

首先，让我们来回顾一下汉语的音节系统——拼音。我们知道，**拼音分为`声母`和`韵母`，`一个声母开头一个韵母结尾`组合起来成为一个完整的`拼音音节`**（这里的讨论背景是计算机中的汉语输入，所以我们不谈音调的问题），所有的汉字都有其对应的拼音音节（多音字则是一个汉字对应多个不同的拼音音节），换句话说，**一个完整的拼音音节就可以定位对应一组汉字**。比如：

```
声母 x + 韵母 iang = xiang -> 像、想、向、相、香.....
```

那么上面一段话，总结起来就是：一个声母开头一个韵母结尾组合起来成为一个完整的拼音音节，一个完整的拼音音节确定一组汉字。那么，再回到上面的例子，我们将`声母x`和`韵母iang`分别绑定到键盘的两个按键上，只需要敲击这两个按键，即可组成`xiang`这个拼音音节。这也就是为什么，我们称这种**`敲击两个按键确定一组备选汉字`的输入法叫`双拼`**的原因。

## 入门

了解了双拼的本质是`敲击两个按键确定汉字`之后，我们就要问了：标准普通话的汉语拼音里，声母23个，韵母39个，一个声母/韵母对应一个按键的话，如此多的音，怎么才能在常规键盘上为他们安排对应的键呢？难道要使用数字区？F区？当然是不现实的。**所以这里需要引入一个`状态`的概念**。什么是所谓的`状态`呢？根据上面的入门，我们知道，一个完整的拼音音节由`一个声母开头一个韵母结尾`组成，除此之外的组合均不能组成一个完整的拼音音节。所以，当我们没有输入时，输入法的状态是`期望一个声母的输入`，而敲入一个声母时，输入法的状态变为`期望一个韵母的输入`，所以，**双拼的解决方案是将声母和韵母层叠的绑定到字母区，因为他们输入状态不同，不会相互影响**。那么细心的朋友又会问了，声母23个可以绑定到字母区没错，但韵母有39个（在实际的使用中没有这么多，39个韵母的说法来自汉语拼音标准中包含最全面的标准），如何将39个韵母绑定道26个按键的字母区呢？这里涉及到比较深入的汉语拼音组成的研究，在此不做详细解释，直接给出结论。这个问题的答案是：将相似但使用情况互斥的韵母绑定到同一个按键。具体怎么操作，我们马上来看。

## 上手

啰嗦这么久，终于要进入正题了。既然我们要输入双拼，那么自然需要选择一个支持双拼输入的输入法。这里我们选择百度输入法（这里仅以其作为演示工具，不就百度公司本身做任何发散），安装完成后是不是就可以开始了呢？不，还有一个微小的问题需要注意：键位方案。

### 什么是键位方案？

什么是键位方案呢？我们每个人的习惯可能是不同的，你喜欢abc对应abc，我喜欢abc对应bcd，凯撒喜欢abc对应tuv。那么我们自然**需要一套统一的规则。这就是所谓的键位方案。**

### 那么键位方案是怎样的呢？

在双拼发展的过程中，因声母韵母分别绑定，不同的用户习惯不太一样，加之双拼输入法多提供了用户自定义按键方案的原因，出现了不止一套广为接受的键位方案。历史久远形成大多数约定的如`自然码`方案、`小鹤双拼`方案，也有输入法制造商提供的自家方案如`微软双拼`方案、`搜狗双拼`方案等。那么选择哪一套好呢？最好的方法当然是都试一遍，选自己觉得顺手的。但是这样太耗费时间精力。**那么我们需要一套筛选标准**。我个人在选用工具时的标准是：方便获取，通用性高，用户量大。落实到双拼方案上，我的选择是`自然码`方案。原因如下：

- 历史悠久
- 几乎所有双拼输入法都默认支持
- 只要有双拼输入法的系统和设备都默认包含
- 用户量大
- 所有按键绑定均在字母区完成（某些方案会使用到标点符号区）

所以我也**建议大家可以优先考虑`自然码`方案**。

### 终于要开始了

在消磨完耐心前，我们终于要开始了。首先我们找到自然码方案所对应的按键绑定表，如下：

![ziranma](https://github.com/MOOOWOOO/articles/blob/master/pictures/ziranma.jpg?raw=true)

其中，**蓝色字母表示声母，红色字母表示韵母**，我们试着输入几个字。比如：你好，世界！

我们先通过全拼将其拆分：ni hao shi jie。然后我们依次查看每个字的声母和韵母，比如第一个字`你-ni`，这个字因为拼音只有两个字母，与全拼并无区别，所以我们继续看下一个字`好-hao`，这个字的拼音出现了三个字母，声母为 h，韵母为 ao，那么我们先在上图找到声母`蓝色的 h`，敲击键盘对应的`按键 h`；接下来在上图找到韵母`红色的ao`，可以看到它绑定在`按键 k`上，所以敲击`按键 k`，此时你会看到输入法的汉字备选框里出现了拼音音节为`hao`的备选字，找一下，敲出`好`字。接下来是一个翘舌音的汉字`世-shi`，对于常规声母只有一个字母，我们很容易的想到直接绑定在对应字母上就好了，但是遇到`翘舌音声母 sh`这样特殊的呢？根据之前介绍的`状态`可知，**在默认状态下，整个字母键区的输入都会被输入法识别为`声母输入`**，所以我们完全可以**找到几个不对应单字母声母的按键，将双字母声母绑定在其上**。所以，回到键位图，可以看到，`蓝色的 sh`被绑定在了`按键 u`，如实，敲击它，再敲击`韵母 i`所对应的`按键 i`，即可得到拼音音节`shi`所对应的备选汉字组了。最后，我们输入`界-jie`，界字的声母很简单，不再赘述，那么它的`韵母 ie`，非单字母韵母，在那里呢？查图可知，`韵母 ie`被绑定在了`按键 x`上，敲击它，从备选列表里找到`界`字吧。

刚刚已经体验了一下双拼输入，是不是有种奇妙的感觉？练习就留给各位之后再做，我们回到图上，可以看到`按键 w r y o s d v`与众不同，均被绑定了两个韵母，这就是之前我们说到的`相似但使用情况互斥的韵母绑定道同一个按键`的情况。

好了，读到这里，双拼入门就完成了，还望各位小伙伴沉下心来，多看键位图，多加练习，短则半日多则两天，一定可以熟练掌握双拼输入法的。**不用刻意去背键位图，唯手熟尔**。祝各位好运！

最后的最后：手机上也有双拼输入法哦，但是**最好就用全键盘输入，这样键位方案与电脑上是一样的**，否则只能很蛋疼的再学一遍。
