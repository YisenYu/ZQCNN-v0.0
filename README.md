ZQCNN-v0.0是ZuoQing参照mini-caffe写的forward库，随便用用

# 更新日志

**2018-08-03日更新**

支持多线程（通过openmp加速）

**2018-07-26日更新**

支持MobileNet-SSD。caffemodel转我用的模型参考export_mobilenet_SSD_caffemodel_to_nchw_binary.m。需要编译出matcaffe才行。
你可以试试这个版本[caffe-ZQ](https://github.com/zuoqing1988/caffe-ZQ)

**2018-06-05日更新**

跟上时代潮流、发布源码。
忘了说需要依赖openblas，我是直接用的mini-caffe里面的那个版本，自己编译出来的很慢。



# Model Zoo

**人脸检测**

[MTCNN](https://pan.baidu.com/s/1f6_wQ2kXiTZFyH6PFIDc2Q) 从[MTCNN](https://github.com/kpzhang93/MTCNN_face_detection_alignment)转的格式

**人脸识别**

[SphereFace04bn256](https://pan.baidu.com/s/1YXt2PLbbUg9-VZITcMw5mQ) LFW约97.8%-97.9%，速度最快

[SphereFace04](https://pan.baidu.com/s/1-Bb6yuU3eAN6U2ZdVsC5Mg) LFW约98.2%

[SphereFace04bn](https://pan.baidu.com/s/18uvL3p7PWRpJcHm00-7ABg) LFW约98.5%

[SphereFace06bn](https://pan.baidu.com/s/1LXjAoJWkWp-CT0sTgIHqfg) LFW约98.7%-99.8%

[SphereFace20](https://pan.baidu.com/s/1fGJU9PfPNBot6qGVeGlcug) LFW约99.2%-99.3%

[Mobile-SphereFace10bn512](https://pan.baidu.com/s/1BEP1pg5s3yJCLA2elqTB0A) LFW约98.6%-98.7%，性价比高

[ArcFace-r50](https://pan.baidu.com/s/1ORhYzZkggSBgSRQ3BbTbDA) LFW约99.75%-99.78%,精度最高，但是很慢

**表情识别**

[FacialEmotion](https://pan.baidu.com/s/1zJtRYv-kSGSCTgpvqc4Iug) 七类表情用Fer2013训练

**目标检测**

[MobileNetSSD](https://pan.baidu.com/s/1ddkVzjQ0kFqUS7atTgrMrw) 从[MobileNet-SSD](https://github.com/chuanqi305/MobileNet-SSD)转的格式

# 相关文章

(1)[人脸特征向量用整数存储精度损失多少？](https://zhuanlan.zhihu.com/p/35904005)

(2)[千万张脸的特征向量，计算相似度提速？](https://zhuanlan.zhihu.com/p/35955061)

(3)[打造一款比mini-caffe更快的Forward库](https://zhuanlan.zhihu.com/p/36410185)

(4)[向量点积的精度问题](https://zhuanlan.zhihu.com/p/36488847)

(5)[ZQCNN支持Depthwise Convolution并用mobilenet改了一把SphereFaceNet-10](https://zhuanlan.zhihu.com/p/36630082)

(6)[跟上时代潮流，发布一些源码](https://zhuanlan.zhihu.com/p/37708639)

(7)[ZQCNN支持SSD，比mini-caffe快大概30%](https://zhuanlan.zhihu.com/p/40634934)

(8)[ZQCNN的SSD支持同一个模型随意改分辨率](https://zhuanlan.zhihu.com/p/40676503)

(9)[ZQCNN格式的99.78%精度的人脸识别模型](https://zhuanlan.zhihu.com/p/41197488)