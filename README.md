# 社招一年半小厂跳大厂面经分享（阿里字节百度滴滴）
大家好，本人之前在一家几百人的十八线小公司，经过时间长达半年的准备还有面试，最终拿到了阿里蚂蚁金服，字节抖音，百度，以及滴滴的offer，当然也还有一众中小公司，比如猿辅导，bigo，探探，boss直聘等，基本上去面试的都通过了（也有挂的），都是后端开发相关岗位。
## 面试经历
本人于19年本科毕业，秋招的时候没有准备好，最终只拿到了一家小公司的offer，当时也是非常遗憾，入职小公司的时候也是立志要跳到一个大公司镀金，这样职业生涯才会更好走一些，毕竟现在大家还是非常认可大厂经历的，所以非常有必要去到大厂镀金。原来准备的是一年离职，最终因为种种原因，被拖了半年才成功实施，一年半跳槽。
   
我是大概入职快满一年的时候开始准备，在准备了两三个月后（主要是背各种基础知识还有准备项目），觉得自己应该是准备好了，然后就去投了几家小公司还有一家中厂，拿来练练手，结果小公司面试通过了，中厂却挂了。我基础知识还有项目准备的很好，被问了很多问题基本都是侃侃而谈，但是中厂一上来就让我写算法题，我算法方面确实没准备好，没写出来再加上自己当时面试的网络环境很差然后就挂了，也就面了二十多分钟一面就挂了。

面试中厂一面挂这事当时对我打击还挺大，因为他问的算法题其实我会，但是就是写不出来，同时也让我了解到自己离大厂其实还是有一段距离，应该回炉重造。在挂了一家中厂之后，我就埋头苦干，去刷算法题了，刷了大概两个多月，刷了200多道题，重新出山，难度由易到难，逐步挑战，最终也是一路过关斩将，面的几乎全过，收割了很多大厂的offer，具体的准备过程接下来会分点叙述，以供参考，谢谢大家。
## 面试准备
### 简历
简历怎么写很重要，直接决定了你这场面试里面的内容，简历写起来牛逼，直接给面试官耳目一新的感觉，我觉得我写的简历还是很不错的，基本都能给面试官不错的印象。

我的简历主要分为三块，基本信息，项目经历（包括公司项目以及个人开源项目），个人技能。

1.基本信息：这块没啥好说的，就是写各种基本信息，简洁高效一点就好了。

2.项目经历：我觉得这块是我写的比较好的一点了，核心关键词就是要有亮点，我的项目包括公司项目与我的个人开源项目。

关于公司项目：

其实我在公司做的就是crud，但是简历上绝不能这么写，要学会包装与抽象，往高大上的一些名词与技术上靠拢，抽出项目中涉及到的比较高大上的名词，比如我的我就抽出了k8s，Redis，以及超过上亿条数据量的MySQL查询与存储优化等。然后对于一些项目中做过的一些事，可能比较有价值，比较高大上，但是不是你做的，是别人做的，你也可以说成是你做的，前提是你要足够了解，面试官如果往下细问，你要能对答如流，不要问到最后被人家揭穿发现不是你做的，那真的很减分。

关于个人开源项目：

这个就是完全的个人加分项了，有了绝对是一大亮点，也可以没有，关键还是看你自己有没有想法，我自己的个人开源项目是一个跨语言及服务治理的RPC框架，在面试的过程当中很多面试官对这个项目很感兴趣，成为了我简历中的一大亮点。我的个人开源项目地址：https://github.com/mwq0106/hirpc-java ，分享不易，希望大家可以给我的这个项目点颗星星吧~~~感谢

3.个人技能：个人技能就是针对自己的技能点做一个简洁高效的总结，列出自己熟悉的技能。

### 基础知识（八股文）

在这里我把基础知识都称为八股文，因为这些东西都是理解加背诵，背过就是会，没背过就是不会，和八股文无异。这些基础知识基本上就是理解加背诵，所以一句话，背就完事了。

那么从哪里开始背呢，前人都帮你总结好了，这里列举一下我的学习资料吧。

1.CsNote：https://github.com/CyC2018/CS-Notes （这个是我复习背诵的主战场，基本上覆盖了大多数面试的知识点，当然也有一些重要的知识点没有覆盖，后面会单独给出；这个教程对于Redis，计算机网络总结的并不好，Redis推荐看我后面列出的，计算机网络的话，暂时还没有更好的，也可以继续看这个教程的，这个教程对于计网的总结太过啰嗦，很多无用偏门内容，但是重要的内容基本都有，所以挑着看就好了，后面有精力我会重新总结一版计网相关的。另外这个教程对于Java线程池，AQS，ThreadLocal等这些重要的知识点也有所缺失，可以再单独查资料学习，后面如果再想到其他重要的知识点会再列出）

2.JavaGuide：https://github.com/Snailclimb/JavaGuide （这个是一个补充知识点，东西太多了，质量不及CsNote，只看过它关于spring那块的总结）

3.Redis相关：https://www.cnblogs.com/kismetv/p/8654978.html （对于常用的中间件要深刻了解他的原理，这是一篇写的很好的深度文章，比你直接看《Redis设计与实现》那本书要好的多，另外Redis扩容重哈希的过程也是一个重要的知识点，可再单独查资料学习）

### 算法

算法是现在面试中必不可少的一环，大多数公司基本都是写不出来就是挂，所以算法这方面一定要下好功夫，我在准备面试的过程当中花费最大的精力就是在准备算法，这个我觉得也是最困难的一关，所以一定要好好重视。在我面试的这些公司当中，问的算法题，只有一道题我是没做过的，其他题全都做过，可以说是非常的爽了，我题目刷的很准，怎么选题来刷也是一门学问。

1.刷题的第一站，必然是刷剑指offer，这个太高频了，很多面试都是从这里面出原题。

2.然后再是LeetCode，LeetCode推荐按分类刷，具体刷哪些分类里面的哪些题呢，我给出一些推荐，按照labuladong算法小抄（https://mp.weixin.qq.com/s/AWsL7G89RtaHyHjRPNJENA ）里面的教程走，然后再是CsNote里面的算法栏目，底下的搜索分类，包括DFS，BFS，回溯子类，全刷；动态规划分类，基本全刷（有些题题解特别少，比较冷门就不用刷了）；然后还有一些其他分类，可以选刷，或者看看题目知道怎么做就行，比较重要的分类包括：双指针，贪心思想，二分查找，分治，链表，树，还有一些就没列了，后面的流程会覆盖到其他重要的分类。按照分类刷的目的是为了掌握这类题的解法套路，这些分类里面的题也可以不用全刷，掌握了大概思想之后，就可以走后面更重要的步骤了。

3.我面了很多公司，遇到的算法题只有一道题没做过，其他全都做过，这是因为我会选题，选出的基本都是高频的题。具体都有哪些题呢，第一站，是剑指offer，超高频；第二站，是LeetCode hot100与LeetCode top面试题，高频；第三站，是LeetCodetop仓库（https://github.com/afatcoder/LeetcodeTop ），这是其他人收集的面试考过的题，按照频率从高往低了刷，准没错，我没刷完他上面的所有题，刷到4频率的题之后就没再刷了，因为后面的太多了，这个看你的个人选择。这三个板块是重中之重，这是进行覆盖式的刷题。

总结一下刷题相关的准备：

1.labuladong算法小抄（https://mp.weixin.qq.com/s/AWsL7G89RtaHyHjRPNJENA ）

2.CsNote算法栏目（https://github.com/CyC2018/CS-Notes ）

3.三板斧覆盖式刷题：剑指offer，LeetCode hot100与LeetCode top面试题，LeetCodetop仓库（https://github.com/afatcoder/LeetcodeTop ）

同时也给出一些小建议：

1.算法题，一定要真的写出来，不能光看觉得我会了就不写了，我当时就犯了这样的错误，导致面试的时候遇到一个自己会做的题结果却没做出来的尴尬（如果你的题量足够多题目又比较简单的话可以跳过），会了和能写出来并且能AC真的两回事。

2.写出来之后一定要去看一下人家的题解，看看人家的思路以及代码是怎么写的，学习一下别人优秀的编程习惯与思路，这样会对你的代码质量以及解题思路有很大提升。

3.推荐直接在网页上编程，不要用本地IDE，因为面试基本都是让网页写题，刚开始可能不习惯，后面就慢慢习惯了，建议直接在LeetCode或者牛客的白板上写代码就好了，没有代码提示与单步调试，一些API多写几次就能记下了，而且这么做才能真正模拟你的面试环境，毕竟现在面试就是网页上编程，你要早点习惯。

4.对于一些题十几分钟二十多分钟没有任何思路，直接去看题解，不要浪费时间，因为你要刷的题很多。

5.对于刷过的题要经常去回顾，去二刷甚至三刷，不然很容易忘，有些题第一次没做出来，做好标记，去看题解，二刷三刷的时候重点去回顾这些题。

6.刷题在于数量更在于质量，我刷的题并不多，200多道题，但是都是精刷，对于同种类型的题一般都能做到触类旁通，所以对于刷过的题一定要彻底弄懂它的原理，都有几种解法，几种思路。

### 项目

这里项目一般就是公司的项目，不过由于我还有个个人开源项目，所以就区分一下公司项目与个人开源项目。

#### 1.公司项目

其实我在公司做的就是crud，但是简历上绝不能这么写，要学会包装与抽象，拿出亮点，往高大上的一些名词与技术上靠拢，抽出项目中涉及到的比较高大上的名词。比如我的我就抽出了k8s，Redis，以及超过上亿条数据量的MySQL查询与存储优化等。然后对于一些项目中做过的一些事，可能比较有价值，比较高大上，但是不是你做的，是别人做的，你也可以说成是你做的，前提是你要足够了解，面试官如果往下细问，你要能对答如流，不要问到最后被人家揭穿发现不是你做的，那真的很减分。

对于项目用到的技术还有中间件，要过一遍，弄清楚它的原理，比如Redis，kafka等，要深入的去理解它的原理。
#### 2.个人开源项目

个人开源项目是一个很大的加分项，会给面试官耳目一新的感觉，我在面试的过程中也深刻体会到了我的个人开源项目带给我的好处。

现在很多应届生简历的开源项目都会写一个RPC框架，造一个RPC的轮子，我这个开源项目也是和RPC相关的，RPC是大型系统后端服务之间调用的基本方式，是一种十分重要的技术，基本上所有的面试官都会或多或少知道一些RPC相关的东西。如果能写一个RPC相关的开源框架，即使没有太多创新，也至少能说明你对于底层原理深究，对于技术的追求，给面试官一个不错的印象。

我的这个RPC开源框架与一般的应届生写的开源框架不同，不是简单的实现一遍RPC就完了，而是尝试了做跨语言还有服务治理的RPC，将dubbo与gRpc进行结合，在其他方面也做出了一些创新，不是重复实现别人的功能。

大家可以参考一下我的作品，将其应用到你的简历上： https://github.com/mwq0106/hirpc-java

走过路过希望大家能帮我的这个开源项目点颗星星~~万分感谢
### 后话

没有在这篇文章中列出各家公司面试问的具体知识点，这是因为知识点很多，授人予鱼不如授人予渔，所有的知识点都在前面的内容中有所覆盖，好好看看基本能做到面试知识点95%以上的覆盖。

要准备的东西很多，如果想要做好充足的准备，就要付出很大的努力，对于要背诵的八股文还有项目经历，我一两个月就准备好了，对于要刷的算法题，又花了两三个月的时间，这些过程中花费了巨大的精力，承受了相当多的痛苦，所以如果真的想完全准备好的话，还是挺艰难的。但是我相信你如果真的能这么坚持下来，拿到大厂offer还是很简单的，祝各位好运。
