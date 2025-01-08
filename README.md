# MSCMRSeg-dataset-transfrom
This code aims to transform a dataset in the h5 format to png. For my purpose, this processing is used to make the dataset suitable for mmsegmentation.

代码将MSCMRSeg的h5格式的数据集转换成了png格式。
如果h5文件有切片则进行切片处理，如果没有则直接转换成png图片
training_slices（训练集）没有切片，training_volumes（验证集）有切片，testing_volumes（测试集）有切片
MSCMRSeg训练集有382+ 75张图片，测试集229张图片
