## Banke Takeaway Data

[TOC]

### 1. Excel Report

####  1. 数据报表

<img src="image.assets/image-20221002220918647.png" alt="image-20221002220918647" style="zoom:50%;" />

##### （1）迷你图

选择指定的数据区域与迷你图的显示区域，生成迷你图

<img src="image.assets/image-20220806163704634.png" alt="image-20220806163704634" style="zoom:67%;" />



##### （2）下拉选择框

<img src="image.assets/image-20220806164009100.png" alt="image-20220806164009100" style="zoom:67%;" />



##### （3）条件格式

根据单元格内容设置条件调整格式，功能：突显特殊值、美化报表、进度条等

<img src="image.assets/image-20220806164258347.png" alt="image-20220806164258347" style="zoom:67%;" />



<img src="image.assets/image-20220806164439218.png" alt="image-20220806164439218" style="zoom:67%;" /><img src="image.assets/image-20220806164459985.png" alt="image-20220806164459985" style="zoom: 50%;" /><img src="image.assets/image-20220806164534292.png" alt="image-20220806164534292" style="zoom:67%;" />

<img src="image.assets/image-20220806164824795.png" alt="image-20220806164824795" style="zoom:50%;" /><img src="image.assets/image-20220806164757342.png" alt="image-20220806164757342" style="zoom: 50%;" />





### 2. Tableau Dash Board

**Dash Board:**

<img src="image.assets/image-20221002220614118.png" alt="image-20221002220614118" style="zoom:50%;" />

<img src="image.assets/image-20221002220644682.png" alt="image-20221002220644682" style="zoom: 50%;" />

#### 2.1 前言

<img src="image.assets/image-20220806171105556.png" alt="image-20220806171105556" style="zoom: 50%;" />

- 连接方式：

  （1）实时：每次计算都会连接一次数据库进行取数

  （2）数据提取：当前连接所涉及的数据全部提取到hyper格式的数据提取（相当于Tableau自己的数据库和对应的类型文件）



- 数据源的保存格式：

  .twb：不带数据，打开需要连接数据

  .twbx：内置数据源



- 数据的类型：

  维度：类别型变量，包含有限的类别，主要用于区分数值型变量，eg 性别、用户ID

  度量：数值型变量，可计算、基于大小通过面积、长短、大小等视觉表达，eg 用户	数量、交易额



- 数据的视觉类型

  位置、长度、角度、方向、形状、面积与体积、颜色与深浅



- 可视化原则

  区分用户：判断可视化设计的观众是谁，从而选择分析、展示的角度

  主次分明：使用适当的强调适当的内容

  真实准确：

  符合大众的认知与审美：颜色一般不要使用超过8种、避免使用3D效果

  五秒原则：5秒钟能看懂

  适当注释：简单说明

  少即是多：迷你图



有轴图形：条形图、折线图、散点图等

无轴图形：饼图、南丁达尔玫瑰图、词云等



创建分层结构：

<img src="image.assets/image-20220808155536046.png" alt="image-20220808155536046" style="zoom:67%;" />

<img src="image.assets/image-20220808155554988.png" alt="image-20220808155554988" style="zoom:67%;" />



#### 2.2 基本图表

拖动属性到“行”或“列”创建图表，通过修改表达方式创建多种图表

<img src="image.assets/image-20220808160116672.png" alt="image-20220808160116672" style="zoom:67%;" />



##### （1）柱状图、条形图

将相关的维度、度量拖至坐标轴即可

<img src="image.assets/image-20220808155339715.png" alt="image-20220808155339715" style="zoom: 50%;" />





<img src="image.assets/image-20220808155319453.png" alt="image-20220808155319453" style="zoom: 50%;" />



##### （2）热力图（突出显示）

通过“方块”、“颜色”表达数值

<img src="image.assets/image-20220808161154512.png" alt="image-20220808161154512" style="zoom: 50%;" />



##### （3）气泡图

通过“文本”、“颜色”表达标签（以“圈”的形式显示），“大小”表达数值

<img src="image.assets/image-20220808161614960.png" alt="image-20220808161614960" style="zoom:50%;" />







##### （4）词云

通过“文本”、“颜色”表达标签（以“文本”的形式显示）、“大小”表达数值

<img src="image.assets/image-20220808161637167.png" alt="image-20220808161637167" style="zoom:50%;" />



##### （5）饼图

选择饼图，显示百分比：将数值度量拖至标签，右键 - “快速表计算” - “合计百分比”，“设置格式”修改字体显示效果

<img src="image.assets/image-20220808162437472.png" alt="image-20220808162437472" style="zoom:50%;" />

环形图

<img src="image.assets/image-20220816234941563.png" alt="image-20220816234941563" style="zoom:50%;" />



##### （6）折线图

折线图趋势线、预测线

<img src="image.assets/image-20220808190319271.png" alt="image-20220808190319271" style="zoom:50%;" />



##### （7）散点图

趋势线

<img src="image.assets/image-20220811155632115.png" alt="image-20220811155632115" style="zoom:50%;" />







##### （8）堆积图

合计百分比

<img src="image.assets/image-20220808171702828.png" alt="image-20220808171702828" style="zoom:50%;" />





##### （9）面积图

<img src="image.assets/image-20220811160354820.png" alt="image-20220811160354820" style="zoom:50%;" />





##### （10）地图

添加字段作为主键、右键属性创建分组

<img src="image.assets/image-20220811165126940.png" alt="image-20220811165126940" style="zoom:50%;" />



<img src="image.assets/image-20220817001029657.png" alt="image-20220817001029657" style="zoom:50%;" />





##### （11）直方图

需要先创建数据桶

<img src="image.assets/image-20220811162220829.png" alt="image-20220811162220829" style="zoom:50%;" />



##### （12）表格

<img src="image.assets/image-20220817014219761.png" alt="image-20220817014219761" style="zoom:50%;" />



#### 2.3 仪表盘

**案例：外卖每日营收数据表**

**（1）明确仪表盘的主题**

主要内容：营收-投放-流量

经营总览（突出显示的文字）

经营数据详情（表格）

每日营收数据（多轴折线图）

每日流量（双轴组合图）

新老可占比、平台占比、门店占比

门店排名（条形图）

投放情况（散点图）







### 附录A. 统计量

**GMV**（Gross Merchandise Volume）：商品交易总额，用来表示用户拍下后最终未支付的订单金额（包括拍下后放入购物车未支付的订单、取消的订单、拒收商品的订单和退货的订单）和拍下后已支付的订单金额之和

GMV = 销售额+取消订单金额+拒收订单金额+退货订单金额



**UV**（Unique visitor）：访问网站的一台电脑客户端为一个访客（**一天内同个访客仅计算一次**）

**PV**（Page visitor）：页面点击量（**累计用户对同一页面多次访问**）



### 附录B. Excel 

建立副本备份数据



Ctrl + Shift + L 筛选器



#### 1.1 数据透视图

（1）插入空白数据透视

<img src="image.assets/image-20220805153340250.png" alt="image-20220805153340250" style="zoom:80%;" />



（2）设置数据透视图字段填充数据透视表

<img src="image.assets/image-20220805153443145.png" alt="image-20220805153443145" style="zoom: 67%;" />

<img src="image.assets/image-20220805154059968.png" alt="image-20220805154059968" style="zoom:67%;" />

（3）插入自定义计算字段

<img src="image.assets/image-20220805153806196.png" alt="image-20220805153806196" style="zoom: 67%;" />

<img src="image.assets/image-20220805154145800.png" alt="image-20220805154145800" style="zoom:67%;" />

（4）插入悬浮切片器（同时应用于其他sheet）

<img src="image.assets/image-20220805153915564.png" alt="image-20220805153915564" style="zoom:67%;" />

<img src="image.assets/image-20220805154003374.png" alt="image-20220805154003374" style="zoom:67%;" />





（5）数据透视图

<img src="image.assets/image-20220805155119838.png" alt="image-20220805155119838" style="zoom:67%;" />

<img src="image.assets/image-20220805155148069.png" alt="image-20220805155148069" style="zoom:67%;" />



#### 1.2 常用函数

通过`=`开头表示函数

通过`$`锁定指定行/列，在拖拽是其值不会变，eg =$B15 列锁定为B，=B$15 行锁定为15



**（1）SUM**

求和

SUM(列/行)   eg A:A

SUM(单/多个单元格)   eg 左上:右下

（通过`,`分隔多个区域）



**（2）SUMIF**

单条件求和

SUMIF(criteria_range, criteria, [sum_range])

SUMIF(条件判断区域, 条件, [求和的数值区域])

（对于条件判断书写：`">="&value`）



**（3）SUMIFS**

多条件求和

SUMIFS(sum_range, criteria_range, criteria, [criteria_range, criteria, ...])



**（4）SUBTOTAL**

根据原表格筛选进行计算（求和、均值、最值...）

SUBTOTAL(function_num, ref1, [ref2, ...])



**（5）IFS、IF**

条件判断

IFS([Something is True1, Value if True1,Something is True2,Value if True2,Something is True3,Value if True3)

依次判断直至TRUE，关键字：`TRUE`



IF(logical_test, value_if_true, value_if_false)

（可嵌套）



**（6）XLOOKUP、VLOOKUP**

XLOOKUP(lookup_value, lookup_array, return_array)

XLOOKUP(查找的值, 查找的区域, 返回值的区域)



VLOOKUP(lookup_value, table_array, col_index_num, match_type)

table_array：包含查找值的列（作为第一列）与返回值的列

col_index_num: 返回值在table_array的第几列



**（7）INDEX**

返回数组指定坐标位置的值（坐标为0返回整行或整列）

**INDEX(array, row_num, [column_num])**



**（8）MATCH**

返回数值指定值的坐标

**MATCH(lookup_value, lookup_array, [match_type])**

match_type：0为精确查找，1为近似查找最大的小于值，-1为最小的大于值



**INDEX与MATCH常搭配使用**

```excel
=SUMIFS(INDEX('拌客源数据1-8月'!$A:$X,0,MATCH(G$111,'拌客源数据1-8月'!$1:$1,0)),'拌客源数据1-8月'!$I:$I,$B112)
```



**（9）DATE、YEAR、MONTH、DAY**

计算日期

```excel
=DATE(YEAR(B39),MONTH(B39)+1,0)  // 每个月的最后一天
```

