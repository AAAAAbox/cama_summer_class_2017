# CAMA-LAB 机器学习暑期研讨班（2017）

## 暑期报告总安排
- 内容
    - 8月23日（周三）：罗宇矗，[强化学习入门](http://www.luoyuchu.com/talk/reinforcement-learning/)
    - 8月28日（周一）：罗宇矗，[深度强化学习简介](http://www.luoyuchu.com/talk/deep-reinforcemnt-learning/)
    - 8月29日（周二）：高飞，图像质量评价及应用
    - 8月30日（周三）：谭敏，基于点击数据的图像识别
    - 8月31日（周四）：余宙，[现代 CNN 网络结构演化](Week_7/slides_zhouyu_CNN_arch_evolution.pdf)
    - 9月05日（周二）：朱素果，视觉跟踪方法研究
    - 9月06日（周三）：匡振中，三维形状表达及其应用
    - 9月07日（周四）：余宙，视觉内容自动问答 VQA
- 地点：东区会议室
- 时间：9:00-11:30
- 安排：(30min 讲解 + 15min 讨论 + 5min 休息) * 3
- 部分报告内容因涉及一些未发表和计划中的工作不会公开，感兴趣的同学可以与老师联系

## 介绍
- 面向对象：准研一学生 + 大一、大二本科生
- 场地：杭电东校区
- 时间：7月17号-9月15号 （工作日：8:00-17:30）
- 内容
    - 机器学习／深度学习 + 计算机视觉应用
    - 课题／项目：选择部分学生，参与老师的研究课题／项目
- 形式
    - 每周
        - 老师指定学习内容，并进行部分讲解
        - 学生自学为主，鼓励自由讨论
        - 定期开会讨论
        - 提交技术报告（算法思想、编程实现、实验结果及分析）
    - 暑期结束
        - 提交大报告、项目总结
        - 选择部分学生，在 2017-18 学年持续参与老师课题
- 讨论方式
    - 线下：东区和老师、研究生学长交流
    - 线上：[Twist](https://twistapp.com/a/17892/) 为主，QQ 群为辅
- 高强度、严要求、安全第一
- 关于作业
    - 每周一会对上周的作业进行讲解
        - 讲解幻灯片和相关资料会上传到 Github
    - 每周三会发布一份上周作业的标准答案
        - 标准答案会发布到 Twist 上
        - 非班上成员可以联系 awolegechu@gmail.com 获取答案

## 整体内容安排
### 机器学习
#### [第一周：热身](Week_1/README.md) （7 月 17 日 - 7 月 22 日）
- Python 编程基础
- 图像表示：
  - 矩阵、颜色空间
  - 图像特征：像素值、颜色直方图、梯度直方图、LBP
  - 作业：图像读写、特征提取
- 回归：
  - 算法：线性回归，线性回归+正则项（L1, L2）
  - 优化：梯度下降法
  - 测度：欧式距离、街区距离、范数、Loss
  - 作业：波士顿房价预测

#### [第二周：分类](Week_2/README.md) （7 月 24 日 - 7 月 29 日）
- 算法：k-NN, Logistic Regression, 决策树
- 作业：
    - MNIST 手写数字识别、CIFAR-10 图像分类
    - 采用第一周的特征 + 第二周的方法（多种组合，对比结果）
    - [井字棋胜负判断](https://inclass.kaggle.com/c/hdu-cama) （需动手实现 ID3 决策树算法）

#### [第三周：经典算法](Week_3/README.md) (8 月 1 日 - 8 月 5 日）
- 支撑向量机 
    - 推荐博文：SVM《理解SVM的三层境界》
- 图像特征：SIFT, Visual BoW
- 作业：[井字棋胜负判断](https://inclass.kaggle.com/c/hdu-cama) （允许使用 scikit-learn 等 Package）

#### [第四周：无监督学习（Unsupervised Feature Learning, Manifold Learning）](Week_4/README.md) (8 月 7 日 - 8 月 12 日）
- Andrew Ng 论文
- 聚类：K-means, K-means++
- 降维：PCA, ICA, ZCA, LLE, AE
- 作业：客户聚类
- 推荐阅读：pluskid 博客

扩展：

- 经典方法：谱聚类、朴素贝叶斯、EM算法、稀疏编码 Sparse Coding
- 集成学习：Adaboost, Random Forest, gdbt (XGBoost)
- 结构化学习 Structured Learning
- 排序学习 Learning to Rank
- 强化学习 Reinforcement Learning
- 模仿学习 Imitation Learning

### 深度学习

#### [第六周：神经网络 DNN&CNN](Week_6/README.md) (8 月 21 日 - 8 月 26 日)
- 概念：卷积, Pooling, Stride, Padding, Data Augmentation, Learning Rate, Momentum, Softmax, ReLU, BP, SGD, Cross-Entropy Loss
- 网络：LeNet, AlexNet, VGGnet, GoogLeNet, ResNet
- 框架：[Keras](https://keras-cn.readthedocs.io/en/latest/)
- 作业：mnist 数字序列识别

#### [第七周：神经网络提升](Week_7/README.md) (8 月 28 日 - 9 月 2 日）
- 内容
    - 神经网络的训练
    - 物体检测与分割
    - 卷积神经网络的可视化与理解
    - 训练卷机神经网络的工程技巧
- 论文阅读：[Deep Learning 推荐阅读论文（余宙）](Deep_Learning_Papers.pdf)
- 作业：SVHN 数字序列识别 


#### 第八周：递归神经网络
- 网络：RNN, LSTM

- 作业：
    - 1）由 Cosin 预测 Sin，自己编程实现网络
    - 2）Image Captioning，使用框架实现

扩展：
- 经典应用论文：[Deep Learning 推荐阅读论文（余宙）](Deep_Learning_Papers.pdf)
- 生成对抗网络：GAN, CGAN, DualGAN, CircleGAN

## 主要人员

 **教师** | - | - | - |  -
--- | --- | --- | --- | ---
 [俞俊](http://camalab.hdu.edu.cn/people/jun_yu/index.html) | [高飞](http://camalab.hdu.edu.cn/people/fei_gao/index.html) | [谭敏](http://camalab.hdu.edu.cn/people/min_tan/index.html) | [余宙](http://camalab.hdu.edu.cn/people/zhou_yu/index.html)  | 朱素果 
 **助教** |  |  |  |  |  
 [罗宇矗](http://www.luoyuchu.com/) | [钱哲琦](https://qzqtechmonster.github.io/) | [朱朝阳](http://chaoyangzhu.com/) | 项晨钞 | 施圣洁 
 张海超 | 孟宣彤 | 郑光剑 | 吴炜晨 |  



