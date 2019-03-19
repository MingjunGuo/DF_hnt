# DF_hnt
I will do some project or take part in some competitions from time to time, and I guess it's a little interesting and magical now.

## 混凝土泵车砼活塞故障预警

## 大致思路
+ EDA&数据预处理：针对不同活塞工况数据：数值型变量提取统计特征（发动机转速、液压油温等），开关型变量、类别型变量进行one-hot编码（搅拌超压信号、设备类型等）
+ 模型选取优化：确定5折交叉验证，选取LightGBM模型进行训练优化
+ 评价结果：以0|1 F1Score 作为评价指标，测试集获得0.623
