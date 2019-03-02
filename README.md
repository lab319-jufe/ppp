# ppp
## 国际比较项目下的PPP计算
### 1哑变量回归与1几何平均两个代码是运用两种的算法来计算基本分类PPP指数
1哑变量回归.py文件运用的算法为CPD法，1几何平均.py文件运用的算法为GEKS法。
最终两种算法结果相同，验证了结果的可靠性
### 2GEKSPPP.py代码目的是求出基本分类以上的ppp（中类ppp以及大类ppp）以及GEKS（中类与大类）
该步骤中采用GEKS法，需要引入各基本分类的支出数据作为权数变量，各个分类权重在各地区权重表格中。
### 2GEKS.py此篇代码作用与命名为2GEKS&PPP的代码相同
都求出了GEKS，但是因为循环方式不同，并未输出ppp。
但是最终两种计算方法求出的GEKS（中类&大类GEKS）相同，在另一层面上验证了结果的可靠性。
### 计算基本分类ppp所需数据在陈·算法压缩包中，计算基本分类以上ppp的各地区权重表在表压缩包中。
### cpd法和GEKS法计算得出的结果分别存在表压缩包和几何平均压缩包中。
