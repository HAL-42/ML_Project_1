* 训练集数据选取：前n%的学习样本作为训练集（非随机选取）
* 测试集数据选取：后1-n%的学习样本作为测试集（非随机选取）

训练集比例 | SVM种类 | 核函数类型 | 启发式 | 其他参数 | 准确率
--|--|--|--|--|--
95% | -s 0 | -t 2 | -h 0 | -c 1 | 81.7%
95% | -s 0 | -t 2 | -h 0 | -c 5 | 82.3%
95% | -s 0 | -t 2 | -h 0 | -c 10 | 82.4%
95% | -s 1 | -t 2 | -h 0 | -n 0.7| 80.9%
95% | -s 1 | -t 2 | -h 0 | -n 0.5| 58%