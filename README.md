# uda_mlnd_capstone

本项目源于State Farm公司发布在Kaggle上的竞赛 (1)，通过车内装置的摄像头来检测司机不安全驾驶的行为，如打电话、手机打字等。识别这些行为，将有利于对用户的驾驶行为进行评估，对不安全的行为予以警示，甚至通过调整保险价格的方式来激励用户安全驾驶。深度学习技术可以对图像进行分类识别，已经在工业上有广泛的应用，可以很好的解决上述问题。

在Kaggle竞赛上，State Farm提供了一批已标注的在视频中截取的彩色图片数据，每个照片对应的标注为十种状态中的一种。
State Farm另提供了若干测试集数据，要求我们对输入数据进行分析，输出该照片对应十种状态的概率。

### 系统要求：
aws P2_Xlarge，或更高配置的GPU主机
Python 2.7
numpy,matplotlib,keras,tensor-flow

### 运行所需时间：
在aws P2_Xlarge上约15小时（每个模型每轮1小时，每模型2-3轮，共6个模型）


------
最终获得了0.187的Kaggle private Score，相当于全部1440多名参赛团队的前50名
