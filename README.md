# 人工智能课后作业
## 1. 人脸姿势识别（人工神经网络）[link](https://github.com/helloMickey/homework/tree/master/Pulsar-search(HTRU_2%20data%20set))
实验数据来源于课本（人工智能——一种现代化方法），简单的使用了sklearn的库做了一些实验对比分析。

(1) 二分类分类器，检测`是否戴眼镜`（sunglasses / open）

(2) 四分类分类器，检测`人体头的朝向`（"left", "right", "straight", "up"）

## 2. 遗传算法 [link](https://github.com/helloMickey/homework/tree/master/genetic-algorithm)
求解f(x) = x + 10*sin(5x) + 7*cos(4x)在给定区间上的最大值，通过简单修改，即可求解`任意函数在任意给定区间上的极大值/极小值`。遗传算法是一种`通用的优化算法`。 

## 3. 启发式搜索[link](https://github.com/helloMickey/homework/tree/master/heuristic-search)、启发式修补[link](https://github.com/helloMickey/homework/tree/master/heurisric-repair-method(N-Queens))
使用启发式搜索的方法求解 `N皇后问题`、`24数码问题`，A*算法的实现

# 其它
## 1. 脉冲星搜索 [link](https://github.com/helloMickey/homework/tree/master/Pulsar-search(HTRU_2%20data%20set))
基于 HTRU_2 数据集（网上可以搜到）做了一些实验分析，对比了不同模型在其上的表现（主要还是调用sklearn中的库）

## 2. 美团爬虫及其热力图 [link](https://github.com/helloMickey/homework/tree/master/crawl-and-data-analysis)
分为爬虫、可视化两部分，爬虫参考了：https://github.com/hahaha108/meituanAppSpider ，可视乎部分将店铺位置信息以热力图形式显示在地图上（百度的API）

## 3. 司法文本分析 [link](https://github.com/helloMickey/homework/tree/master/judicial-data-analysis)
爬虫+数据分析，爬虫参考：https://github.com/FanhuaandLuomu/pkulaw_spider ；数据处理部分通过`结巴分词`和`TF-IDF`对文本进行分词和词权重修改，并对词向量进行关联性分析。