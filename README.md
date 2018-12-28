这个博客有说明：https://cloud.tencent.com/developer/article/1117362

这个参数参数也很简单，可以学习ncnn 模型导入的典型。

mtcnn 模型文件路径 图片路径

例如: mtcnn ../models ../sample.jpg

用cmake即可进行编译示例代码，详情见CMakeLists.txt。



移除NCNN 与mtcnn无关的层，

梳理ncnn的一些逻辑代码。

简单做了一些适配和优化。

砍掉一些边边角角。

不依赖opencv等第三方库。



# MTCNN
MTCNN face detection implementation base on NCNN

![image](https://github.com/cpuimage/MTCNN/blob/master/result.jpg)

caffe模型转换参照项目:

https://github.com/ElegantGod/ncnn

NCNN项目:

https://github.com/Tencent/ncnn


