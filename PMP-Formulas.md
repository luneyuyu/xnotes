# PMP公式大全 - 传说中的闲人
> 整理参考PMBOK第五版

## 项目时间管理
编号 | 名称 | 公式 | 含义 | 其他
:---------- | ---------------: | :--------------- | :--------------- | :---------------
1 | 三点估算 | (P+4M+O)/6 | O：最乐观时间；P：最悲观时间；M：最可能时间 |
2 | 标准差 | (P-O)/6 |  |
3 | 最早结束时间:EF | ES+duration-1 |  |
4 | 最早开始时间:ES | ES+predecessor+1 |  |
5 | 最晚结束时间:LF | LS+successor-1 |  |
6 | 最晚开始时间:LS | LF+duration+1 |  |
7 | 总浮动时间:TF | LS-ES or LF-EF |  |
8 | 自由浮动时间:FF | ES-EF | ES(Successor)/EF(Predecessor) |


ES(最早开始) | duration(持续时间 | EF(最早结束)
:-: | :-: | :-: 
 | Task Name(活动名称) | 
LS(最晚开始) | TF(总浮动时间) | LF(最晚结束)


## 项目成本管理（EVM:挣值管理）
编号 | 名称 | 公式 | 含义 | 其他
:---------- | ---------------: | :--------------- | :--------------- | :---------------
1 | 完工预算：BAC | 没有公式-这就是项目预算 | 将在这个项目上花多少钱 | 告诉赞助人他将从这个项目得到的总价值
2 | 计划价值：PV | BAC x 计划/完成百分比 | 进度要求应该花多少钱 | 得出计划要求的到目前为止应该交付多少价值
3 | 挣值：EV | BAC x 实际/完成百分比 | 实际上所挣的项目价值 | 把团队已经完成的工作量转换为用钱衡量的价值
4 | 实际成本：AC | 在项目上实际所花的钱 | 目前为止实际上已经花了多少钱 | 你花了多少钱并不一定与得到的价值一致
5 | 进度绩效指数：SPI | EV/PV | 进度超前还是滞后 | 确认是否交付了进度要求的本该交付的价值
6 | 进度差异：SV | EV-PV | 进度超前或滞后多少 | 用钱来衡量进度超前或滞后多少
7 | 成本绩效指数：CPI | EV/AC | 是否在预算内 | 赞助人总是对这个盈亏底线最感兴趣
8 | 成本差异：CV | EV-AC | 缩减或超出多少预算 | 赞助人需要知道投入了多少成本来得到你交付的价值
9 | 完工尚需绩效指数：TCPI | (BAC-EV)/(BAC-AC) | 项目必须有怎样的绩效才能保证不超出预算 | 可以利用这个指数预测是否能保持在预算内
10 | 完工估算：EAC | AC+ETC |  | 以前的估算假设不成立
11 | 完工估算：EAC | BAC/CPI | 预测项目完成时的总成本。本公式是重点 | 有偏差且偏差典型
12 | 完工估算：EAC | AC+(BAC-EV) |  | 无偏差或偏差不典型
13 | 完工尚需估算：ETC | EAC-AC | 项目余下部分最终要花多少钱 | 可以使用EAC、ETC和VAC来预测项目完成时的挣值数
14 | 完工尚需估算：ETC | 自下而上再估算 | 缩减或超出多少预算 | 可以使用EAC、ETC和VAC来预测项目完成时的挣值数
15 | 完工偏差：VAC | BAC-EAC | 花费超出预算，VAC会是负值 | 可以使用EAC、ETC和VAC来预测项目完成时的挣值数
> 记住：更低(Lower) = 失败(Loser)。如果CPI或SPI小于1，或者CV或者SV为负值，就说明你有麻烦了


***

#英文版
## TIME(chapter6)


## COST(chapter7)



## QUALITY(chapter8)



## COMMUNICATION(chapter10)



## RISK(chapter11)



## PROCUREMENT(chapter12)

























#中文版

## 时间管理



## 成本管理



## 质量管理



## 沟通管理



## 风险管理



## 采购管理
