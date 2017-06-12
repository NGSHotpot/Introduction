# NGSHotpot 简介
>Nothing in Biology Makes Sense Except in the Light of Evolution. –Theodosius Dobzhansky (1973) 
>二十一世纪是生命科学的世纪。 –by who? (when?)

Next Generation Sequencing (NGS，可以戏称为农工商)感觉上应该也该整上一句作为从业人员见面接头的行话。随着NGS（“农工商”）的快速发展，近来大城市是基本已经看不到店面了，paper里倒是越见越多，搞得大家都觉得这个缩写不再高大上，过一阵再换个id我们一点也不会觉得惊奇。知道香农熵的定义entropy到底是什么意思吗？小道八卦是当时统计上已经有了这个概念，而香农的好基友冯诺伊曼提议：no one knows what entropy really is, so in a debate you will always have the advantage [1]。So，搞科研还是得有靠谱的好基友的，现在谁还知道统计上先搞出来的这个玩意儿叫啥？

根据National Human Genome Research Institute (NHGRI)的统计，2001年使用桑格测序方法每百万碱基花费大于5000美元，而2015年使用NGS得到一百万剪辑序列仅需0.014美元，个中趋势如下图 [2]。单测序市场的预估之大，不容错过，到2021年（眼看着也没几年了），有12 billion USD [3]。以前大概还只是科研机构来贡献，现在目测还得加上各种临床检验的尝试，筛药贡献的数据。 

![](https://github.com/NGSHotpot/Introduction/blob/master/image1.png ==600x)

朋友们，这是超越摩尔定律的趋势。那你知道摩尔定律是如下5个点猜出来的吗[3]？就这5个点的带来的预期，21世纪的码农就有无数的砖可以搬。那NGS这种超摩尔定律的趋势代表了什么呢？越来越多的数据和越来越多具有想象力的应用，即各种棱角可以搬的砖，只有想象力制约了砖的形状。就测序方法层面，从一开始的全基因组测序一步步走上了功能化解读的ChIP-seq，RNA-seq，一波走起到GRO-seq，ATAC-seq，Hi-C，HiChIP，eCLIP等等。就工具层面我们看到例如单就RNA-seq而言，前几年的一波TopHat+Cufflinks+Cuffdiff，现在又一波HISAT+StringTie+Ballgown等工具的翻新。考虑到单分子技术的火热，上述两条分类又整了一波单分子潮流。就大型合作方面，ENCODE，Roadmap，Blueprint，TCGA一波又一波地刷屏。就应用型公司方面，抱歉，没收推广费，不发软文。 

![](https://github.com/NGSHotpot/Introduction/blob/master/image2.png)

So，不要再苦恼现在吃的苦都是当时选生物专业时脑子进的水了，写上程序，整点统计，想想算法，跑跑流程，其实和别的理工科专业也没有太大差别，除了我们可能有超摩尔定律支持的前途。

哥，来份NGS Hotpot，我们从技术层面好好聊。

>Thanks to NGS, all 21th biology is computational biology. –NGS Hotpot (2017)

# Reference

1. http://www.eoht.info/page/Neumann-Shannon+anecdote
2. https://www.genome.gov/sequencingcostsdata/
3. Moore G E. Cramming more components onto integrated circuits[J]. Proceedings of the IEEE, 1998, 86(1): 82-85.
4. https://www.mordorintelligence.com/industry-reports/global-next-generation-sequencing-ngs-market-industry
