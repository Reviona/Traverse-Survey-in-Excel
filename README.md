# Traverse-Survey-in-Excel 导线测量的Excel自动计算
Auto fill the traverse table in Excel.

## 算法背景
>导线测量是指将一系列测点依相邻次序连成折线形式，并测定各折线边的边长和转折角，再根据起始数据推算各测点平面坐标的技术与方法。  
将相邻控制点连成直线所构成的折线称为导线，相应的控制点称为导线点。导线测量就是依次测定导线边的水平距离与两相邻导线边的水平夹角，根据起算数据，推算各边的方位角，求出导线点的平面坐标。  
>>导线的布设形式
按照不同的情况和要求，单一导线可布设为附合导线、闭合导线和支导线，如图《导线的布设形式》所示。它是建立小地区平面控制网的常用方法，常用于地物分布复杂的建筑区，视线障碍多的隐蔽区和带状区。  
(1)附合导线，导线起始于一个已知控制点B而终止于另一个已知控制点C，已知控制点E可以有一条或几条定边与之相连接，也可以没有定向边与之相连接。该导线形式具有3个检核条件，包括1个坐标方位角条件和2个坐标增量条件。  
(2)闭合导线，由一个已知控制点A出发，最终又回到这一点，形成一个闭合多边形在闭合导线的已知控制点上至少应有一条定向边与之相连接。该导线形式具有3个检核条件，包括1个多边形内角和条件和2个坐标增量条件。  
(3)支导线，从一个已知控制点c出发，既不附合于另一个已知控制点，也不闭合于原来的起始控制点。由于支导线缺乏检核条件，故一般只限于在地形测量的图根导线中采用。

## 版本历史

### v1.0
闭合导线表格的自动生成和计算。  
[![oUvTPJ.png](https://z3.ax1x.com/2021/12/03/oUvTPJ.png)](https://imgtu.com/i/oUvTPJ)