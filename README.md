
## 区域PPP的计算

本代码是江西财经大学2017级应用统计硕士王润奇毕业论文中研究所用代码，论文题目为《基于虚拟产品法的横比价格指数方法研究》

### 本代码由江西财经大学2018级应用统计硕士陈玲倩完成
### 如有引用或使用此代码，请预先告知指导教师李峰，邮箱为lifeng@jxufe.edu.cn
### 所有数据均为模拟数据，仅为验证算法而编写，其中涉及到的地名为编写数据时的直观依据

此版本代码最后更新时间为2019/3/29。


研究得到国家统计局江西调查总队、江西省统计局、江西财经大学、上饶调查队联合研究的《国际比较项目下的横比价格指数》课题支持。
  
课题负责人：赖建军   
课题组成员：逯虹 张启良 李峰 陈军 颜峰 柏寅弘 王润奇 陈玲倩 

### 四个代码文件目的是计算区域ppp，具体内容如下：

#### 1-1基本分类ppp（GEKS法）与1-2基本分类ppp（CPD法）是运用两种的算法来计算基本分类PPP指数
1.1基本分类ppp（GEKS法）.py文件运用的算法为GEKS法，  
1.2基本分类ppp（CPD法）.py文件运用的算法为CPD法。
最终两种算法结果相同，验证了结果的可靠性。

#### 2-1基本分类以上的ppp（GEKS&PPP）代码目的是求出基本分类以上的ppp（中类ppp以及大类ppp）以及GEKS（中类与大类）
该步骤中采用GEKS法，需要引入各基本分类的支出数据作为权数变量，各个分类权重在各地区权重表格中。

#### 2-2基本分类以上的ppp（GEKS）同样是求出GEKS（中类与大类）
但是因为循环方式不同，并未输出ppp。
但是最终两种计算方法求出的GEKS（中类&大类GEKS）相同，在另一层面上验证了结果的可靠性。

#### 四个代码文件中均有注释
##### RPPP示例文件夹
计算RPPP所需数据——11个地区的表格，以及各地区权重表均在RPPP文件夹下。
CPD法和GEKS法计算得出的结果分别存在CPD算法输出结果压缩包和GEKS算法输出结果压缩包中。


##### ICP算法文件夹
该文件夹下是国际比较项目下的PPP计算示例
