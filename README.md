# CarPlateIdentity
车牌识别
这个实践项目我的环境是python3.6、OpenCV3.3.0,tensorflow1.12.0
车牌过滤和字符识别部分用卷积神经网络完成的，训练数据集来自 https://github.com/detectRecog/CCPD
项目详细说明见CSDN：https://blog.csdn.net/GK_2014/article/details/84779166

carIdentityData目录下：
cnn_char_train：为字符训练模型
   包含字符训练集数据：char_train和字符测试集数据：char_test

cnn_plate_train：为车牌检测训练模型
   包含车牌训练集数据：plate_train和车牌测试集数据：char_plate

images下保存实际测试时用到的数据：pictures
结果保存在:opencv_output