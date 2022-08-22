# ML-Eg-Eformation-HeatMap-FitingML-CrossValid-SR_wrong-predict_excel
ML-Eg-Eformation-HeatMap-FitingML-CrossValid-SR_wrong-predict_excel; accuracy should be further improved


##输入文件需准备好：

Bandgap.xlsx 原始数据（输入特征和输出标签band gap 都有）


Bandgap Predict.xlsx   不含标签的预测集需要提前准备好


Periodic Table of Elements.csv   元素的一些描述符， 可以加个容忍因子和八面体因子（对于钙钛矿）


注意皮尔逊热图需要自己手动删除多余的特征，需要设定某阈值，例如先删除相对于输出标签-0.1<feature<0.1的特征，再删除特征之前相关系数绝对值>0.9 （0.8等，视情况而定）
