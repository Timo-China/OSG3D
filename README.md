# OSG3D
学习OSG和OSGEarth的练习之作

下载后，使用VS2013(或以上版本)打开OSG3D.sln，即可编译运行(其中依赖Qt库);

包括功能：
Geometry绘制：点、线、面；
测量分析：长度测量，高度测量，面积测量，水淹分析；
通视分析：两点通视，区域通视；
Overlay测试，全球网格测试；
控制avatar的上下左右移动。

增加一个工程OSGLWidget：
验证使用QOpenGLWidget/QGLWidget的方式嵌入OSG；
增加使用OSG而不用OSGEarth的方式添加一个三维数字球(只能玩)