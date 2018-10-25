# bilstm-crf
双向lstm+crf 序列标注,国科大自然语言处理课程作业
完成地名、人名、组织名的标注
# 思路
1.使用source_data.txt里面的语料训练词向量
2.设计一个双向的lstm神经网络训练得到各节点特征函数
3.lstm的末尾挂上一层crf网络,用以训练得到边特征函数
4.定义损失函数为log
5.划分，验证集
6.训练
7.优化调参
8.测试，计算F1
