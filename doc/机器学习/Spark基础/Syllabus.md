# 组队学习内容设计目录模板

# SPARK组队学习内容目录

 1. 运行原理，RDD设计，DAG，安装与使用
	- 内容
      第1章 Spark的设计与运行原理（大概了解）
	       1.1 Spark简介
           1.2 Spark运行架构
           1.3 RDD的设计与运行原理
           1.4 Spark的部署模式
      第2章 Spark的安装与使用（主要内容）
           2.1 Spark的安装和使用 （如果想在window上安装，参考https://blog.csdn.net/SummerHmh/article/details/89518567，之后可以用pyspark或者jupyter上进行学习）
		   2.2 第一个Spark应用程序：WordCount
	- 扩展题目
      1.spark 和 mapreduce有哪些区别，请用具体的例子说明？
	    a. Spark提供了内存计算，中间结果直接放到内存中
		b. Spark是基于线程调度
		c. 更丰富的算子更为灵活的调度方式DAG
	  2.rdd的本质是什么？
	    分布式对象集合，本质上是一个只读的分区记录集合，每个RDD可以分成多个分区，每个分区就是一个数据集片段，并且一个RDD的不同分区可以被保存到集群中不同的节点上，从而可以在集群中的不同节点上进行并行计算
      
 2. RDD编程，熟悉算子，读写文件
	- 内容
      第3章 Spark编程基础
		3.1 Spark入门：RDD编程
		3.2 Spark入门：键值对RDD
		3.3 Spark入门：共享变量（提升-分布式必备）
		3.4 数据读写
		3.4.1 Spark入门：文件数据读写
	- 扩展题目（此题目要求比较高，有兴趣的可以做做）
      PAT排名器 https://pintia.cn/problem-sets/16/problems/677
	  a. 按人进行groupby
	  b. 按照题目groupby
	  c. 处理-1的情况
	  d. 处理未做的题目
	  e. 聚合处理
 3. DataFrame,SparkSQL和Spark Streaming
	- 内容
	第4章 SparkSQL
		4.1 Spark SQL简介
		4.2 DataFrame与RDD的区别
		4.3 DataFrame的创建
		4.4 从RDD转换得到DataFrame
		4.5.2 通过JDBC连接数据库(DataFrame)
	第5章 Spark Streaming
		5.1 流计算简介
		5.2 Spark Streaming简介
		5.3 DStream操作
			5.3.1 DStream操作概述
	- 扩展题目
      spark sql的运行机制
      	a.解析sql生成逻辑执行计划
	  	b.优化逻辑执行计划
	  	c.生成物理执行计划
	  	d.执行物理执行计划（一系列RDD操作）
 4. MLlib流设计，特征工程
	- 内容
	第6章 Spark MLlib
		6.1 Spark MLlib简介
		6.2 机器学习工作流
			6.2.1 机器学习工作流(ML Pipelines) 
			6.2.2 构建一个机器学习工作流
		6.3 特征抽取、转化和选择
			6.3.1 特征抽取：TF-IDF
			6.3.4 特征变换：标签和索引的转化
			6.3.5 特征选取：卡方选择器
 5. 逻辑回归，决策树
	- 内容
	6.4.1 逻辑斯蒂回归分类器
	6.4.2 决策树分类器

