# CRNN(CNN+RNN+CTCLoss)
Text recognition



# 如何去测试

1.下载模型放在./model中
链接：https://pan.baidu.com/s/1b52JphR357INqWdDCb1-WA 
提取码：0et2 

2.将test.zip文件解压到当前文件夹

3.运行模型

    python3 test_crnn.py
 
 
# 如何去train
1.处理train 数据集

    python3 ./utils/make_data.py

2.训练网络
    
    python3 train.py   
    
