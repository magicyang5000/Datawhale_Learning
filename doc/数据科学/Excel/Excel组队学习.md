组队学习内容大纲
 * 组队学习基本信息
    * 组队学习名称：Excel入门
    * 组队学习周期：12天
    * 组队学习类型：理论，案例实操
    * 组队学习学习者定位：小白，0基础亦可
    * 组队学习难度等级：简单
    * 先修组队学习：无
    * 后续推荐组队学习：MySQL、Python等
* 组队学习目标设计
    * 知识目标
        * 了解Excel的界面构成
        * 了解Excel常用函数
        * 熟练掌握透视表以及绘图
        * 掌握Excel函数的配合使用
* 组队学习设计进度安排
任务一、界面和基础操作(2天)
任务二、基础函数（2天）
任务三、match index 和vlookup函数 和双条件查找匹配 （2天）
任务四、基础图表（4天）
任务五、数据透视表（2天）

任务一、界面和基础操作(2天)
 基础界面

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918173751629.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)文件操作
新建workbook 新建sheet/移动sheet/重命名sheet/修改sheet颜色 sheet种类: 工作表/图表/宏表等 保存为xls/xlsx/csv
基础单元格操作
输入数据 数据格式 合并单元格 自动填充 选择性粘贴 去重 分列 排序 筛选 条件格式 插入下拉列表 行高列宽设置 冻结首行首列 边框 单元格换行
作业:
任务一 参考下图。给Excel截图并标注功能。 建议将开始/插入等功能区里的具体内容模块也标注。 
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918174752454.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)p.s 根据自己的需求决定详细程度。目的是对整个excel的功能布局有个大致了解，之后要用到的时候知道去哪里找即可。
任务二 生成一个行高30，列宽15（第六列列宽45），名为“Excel组队学习”的表，要求如下： 
1、第一列为职位ID，背景色为浅蓝； 
2、第二列为职位类型，字体颜色为红色；
3、第三列为学历，每个单元格有下拉列表，选项为大专、本科、硕士、博士； 
4、第四列为行业方向，单元格边框为红色虚线；
5、第五列为薪资水平，数据类型为货币，保留两位小数；
6、第六列为职位标签。 
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918174903599.png)
任务三 操作对象为任务一生成的“Excel组队学习”表 2.1 冻结窗格1-3行，效果如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203056159.png)

2.2 将第六列分列，效果如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203113904.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)

2.3 利用条件格式，将薪资列大于8000的收入填充为深绿色，并将它们筛选出来，效果如下
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203130113.png)
2.4 第二列将重复值删除，只保留唯一值，效果如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203154717.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)任务二、基础函数（2天）
单元格引用
混合引用 绝对引用 相对引用
运算符
文本函数
连接符 & 字符提取 left/right/mid text函数 常与find配合
逻辑函数
if函数 单条件 多条件
计算函数
max min average sum count sumif countif sumproduct
作业
任务一 1.1将列salary最低工资提取出来，假如单元格为“10k以上”、“8k以下”等，最低工资直接为10和8，效果如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203220966.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)1.2 计算北京最低工资的平均值？ 
1.3 最低工资平均值最低的城市是哪一个？ 
1.4 北京本科的招聘中，最低工资介于7-11（大于7小于11）的岗位有多少个？
任务二 将职位标签（positionLables）中，包含“大数据”的岗位筛选出来。
任务三 将最低工资分段，（0,4]为低，（4,8]为中，8以上为高。



任务三、match index 和vlookup函数 和双条件查找匹配 （2天）
vlookup函数用法
vlookup、hlookup、lookup函数的用法和三者的区别
match和index
match函数用法 index函数用法 用match和index函数实现vlookup功能
双条件查找
https://jingyan.baidu.com/article/fd8044faf87ea55031137af6.html
作业
(请下载提供的数据集《DataAnalyst》) 链接：https://pan.baidu.com/s/1sCaFkQ9DoxYE-FyiY2ewPA  提取码：f55z 
1.用vlookup函数 查找以下公司的 companyId | companyFullName | |:----| | 上海云贝网络科技有限公司 | | 携程计算机技术（上海）有限公司 | | 浙江康健绿线网络技术有限公司 | | 久亿财富（北京）投资有限公司 | | 杭州木瓜科技有限公司 | | 思特沃克软件技术（成都）有限公司 | | 北京金山云网络技术有限公司 |
2.用match和index函数实现第一题的功能
3.用match和index函数查找以下id对应的公司名称，注意id是横向排列的 | companyId | 127200 | 151079 | 22225 | |----|----|----|----|
4.请根据companyId和postionId两个条件查找对应的工资水平 | companyId | positionId | salary | |:----|:----|:----| | 62 | 938038 | | | 1575 | 1157620 | | | 157392 | 2574696 | |
请思考，是否会存在相同的公司id和职位di对应多种工资水平，如果有请查找出来。 并思考，如果存在多种的情况，目前的公式还能不能用？


任务四、基础图表（4天）
了解excel有哪些图表类型
1、柱形图 2、折线图 3、饼图 4、条形图 5、组合图 6、散点图 。
andrew abela大神制作的图表类型选择指南
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203304902.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203317837.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)图表的构成要素
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203347882.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)作业：
请按要求自行选择类型作图
任务一：统计各个城市对于数据分析师的需求情况
任务二：统计对求职者学历要求的情况
任务三：统计对求职者工作经验要求的情况
任务四：统计各种职位的需求情况
任务五：统计不同城市不同行业对于数据分析师的需求情况
任务六：统计不同城市的平均工资水平情况
任务七：统计不同行业的平均工资水平情况
任务八：统计不同职位的需求情况
任务九：分别统计北京, 上海，深圳，广州四个城市 不同行业和学历的工资分布情况
任务十：分别统计北京, 上海，深圳，广州四个城市 不同行业和工作年限的工资分布情况
P.S. 请注意几点：
①以上都是开放式的，并不一定存在标准唯一答案
②有很多需要先进行数据处理，比如平均工资水平的定义和求解、比如所谓的“不同职位”
③请注意图表的构成要素，自行决定是否需要添加数据标签、坐标轴标题等
④图表不是选定一种类型，然后往里面拖数据就完事的。需要多思考应该怎么样去呈现这些数据。 比如 ：
图表的配色 不要太多颜色，且所有的图表配色风格要保持一致
图表的分布，比如柱状图，你的横坐标应该根据柱子大小从大到小排列
图表画完，你应该有一两句总结性的话。即图表展现的规律或你想表达的观点。
你可以假设这是一份你向公司大老板汇报的图表结果，这次汇报会决定你是否升职为公司数据分析总监:-）。 如何尽可能清晰 简练的用图表表达出你的意思和数据规律情况







任务五、数据透视表（2天）
创建数据透视表
数据透视表字段与区域
筛选 行 列 值
如何改变数据透视表布局
分类汇总 总计 报表布局
数据透视表刷新
手动刷新 设置全部刷新 打开文件时自动刷新
实现数据分段统计
自动等距离组合 自定义组合
变更值汇总依据
求和 计数 平均值 最大/最小值 乘积
设置三种值百分比
总计百分比 分类百分比
计算字段和计算项
（补充，非必修）学习数据透视图
作业
任务一 1.1统计汇总每个城市大专、本科、硕士、博士的招聘人数，对学历没有要求的招聘不计算在内，效果如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203425716.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)1.2统计汇总每个城市大专、本科、硕士、博士的最低工资平均值，对学历没有要求的招聘不计算在内，效果图如下： 
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203448235.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTgxMDU0MA==,size_16,color_FFFFFF,t_70)任务二 使用筛选器，统计每个城市，不同的工作年限，不同的学历，最低工资的平均值是多少，对学历和工作年限没有要求的不计算在内，效果如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190918203518754.png)
