# 材质概述

###### *version :2.1.0beta   Update:2019-5-14*

材质就是物体的材料质感，例如木头、金属、玻璃、毛发、水等，它们的粗糙度、光泽度、反射、透明、颜色、纹理等材质属性都有所不同。

大多数3D引擎中都有独立的材质类用于程序代码控制，三维制作软件中材质处理也是最重要的部分之一，游戏美术开发者们经常有一句话，在3D游戏场景制作中，三分看模型，七分靠材质。

材质的种类也有很多，在三维制作软件中有标准材质、多维材质、合成材质、双面材质、光线跟踪材质等。在LayaAir 3D引擎中目前主要支持的是标准材质 **BlinnPhongMaterial** ,**UnlitMaterail**,**PBRStandardMaterial** 等。