# learn-webgl


## obj 文件 

使用建模软件blender生成obj文件：

V 顶点vertex

Vt 贴图坐标点

Vn 顶点法线

usemtl 材质： F是面，后面分别对应 顶点索引 / 纹理坐标索引 / 法线索引

2D文字是可以通过分析获得3D文字模型数据的，将文字写到canvas上之后读取像素，获取路径。

理论上任何2D文字都能转3D

![](http://static.open-open.com/lib/uploadImg/20170316/20170316141438_836.gif)

## 参考
1. [使用blender快速生成一个简单的3D世界](https://github.com/vorshen/simple-3d-text-universe/blob/master/doc/doc.md)