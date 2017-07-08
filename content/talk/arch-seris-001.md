+++
draft = false
date = "2017-07-08T22:08:25+08:00"
title = "架构培训系列001-高性能服务开发"
Tags = ["architecture","server","socket","develop"]
+++

> 架构培训系列课件，总共有四课：
>
> 第一课，高性能服务开发
>
> 第二课，服务框架及分布式原理
>
> 第三课，云计算及微服务架构
>
> 第四课，分组讨论
>
> 以下为第一课内容：



​						 《高性能服务开发》

![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8701.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8702.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8703.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8704.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8705.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8706.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8707.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8708.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8709.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8710.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8711.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8712.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8713.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8714.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8715.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8716.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8717.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8718.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8719.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8720.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8721.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8722.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8723.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8724.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8725.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8726.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8727.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8728.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8729.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8730.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8731.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8732.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8733.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8734.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8735.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8736.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8737.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8738.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8739.jpg)
![sliceimg](http://osrjkumus.bkt.clouddn.com/arch-001/%E5%B9%BB%E7%81%AF%E7%89%8740.jpg)