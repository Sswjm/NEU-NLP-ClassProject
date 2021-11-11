# NEU-NLP-ClassProject
本项目为东北大学自然语言处理选修课程的课程作业部分，项目内容为使用LSTM实现一个神经网络语言模型（仅使用nn.Linear与nn.Parameter，不使用Pytorch官方提供的LSTM接口）
# Requirements
Pytorch == 1.8.1
# 相关文件及含义
models：存储训练后的模型

penn_small：语料数据

give_valid_test.py：数据预处理

oriLSTMLM.py：使用官方提供的LSTM接口搭建的神经网络语言模型

LSTMLM.py：修改后的仅使用nn.Linear和nn.Parameter搭建的LSTM神经网络语言模型

douLSTMLM.py: 根据LSTMLM.py修改实现的双层LSTM神经网络语言模型
# 课程地址
[自然语言处理：深度学习方法](https://www.nlplab.com/courses/nlp2021/)
