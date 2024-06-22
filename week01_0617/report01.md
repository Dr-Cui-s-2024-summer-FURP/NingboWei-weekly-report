# report for week01
## 1.self study of lsaac sim
- **lsaac sim** is a platform to do design, simulation, testing and training AI_base robot in a physical based virtual enviornment.
- 可使用USD框架接受其他文件格式，创建3D场景
- since my persional devices do not support to run lsaac sim, I will first ignore these part.
## 2.basic understanding of CNN(convolutional neural network):
### what is CNN:
- CNN is adeep learning model for computer vision tasks, like image classfication and object detection. It can automatically learn feature representations from images without human extraction.
- CNN consists of following layers:
    - Input layer(输入层) -- 对数据进行预处理，包括去均值，归一化和PCA/白化
    - Convolutional layer(卷基层) -- 局部关联与窗口滑动，没太看懂，，，
    - Action layer(激活层) -- 也称作Relu激励层，把卷积层数据做非线性映射，使用the rectified liner unit作为激活函数
    - Pooling layer(池化层) -- 夹在连续的卷积层中间，用于压缩数据与参数(如压缩图像)，减小过拟合
    - Fully Connected Layer(全链接层)
### Framework for training/using cnn:
- PyTorch: come from facebook
- TensorFlow: come from google
## 3.PoseCNN and PointNet algorithm
### PoseCNN: 
- a model base on CNN
- it can estimate the 6D position of an onject(3D position+3D orientation)
- it first use CNN to extract image feature(特征)， then predicts 6D pose.
### PointNet algorithm
- a neural network for processing point cloud data(点云数据)
- different from CNN

## For the following weeks:
- 尝试复现PoseCNN与PointNet
- 因为自己目前正在腾讯实习，所以署研进度会稍慢，但会尽力参与
