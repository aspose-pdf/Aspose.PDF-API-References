---
title: ImagePlacement
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示放置到 Pdf 文档页面的图像的特征。
type: docs
weight: 171
url: /zh/java/com.aspose.pdf/imageplacement/
---
**遗产：**
java.lang.Object
```
public final class ImagePlacement
```

表示放置到 Pdf 文档页面的图像的特征。

--------------------

```
The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions.
 
  
 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //创建 ImagePlacementAbsorber 对象以执行图像放置搜索
 ImagePlacementAbsorber abs = new ImagePlacementAbsorber();
 //接受第一页的吸收器
 doc.getPages().get_Item(1).accept(abs);
 //检索具有可见尺寸的图像
 for (ImagePlacement imagePlacement : ```
(Iterable)
```abs.getImagePlacements())
 {
     BufferedImage scaledImage;
     ByteArrayOutputStream imageStream = new ByteArrayOutputStream())
     
         //从资源中检索图像
         imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png);
         BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream);
         //创建具有实际尺寸的新位图
         scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight());
     
 }
```

--------------------

将图像放置到页面时，它可能具有资源中定义的物理尺寸以外的尺寸。 ImagePlacement 对象旨在提供尺寸、分辨率等信息。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingParameters()](#getCompositingParameters--) | 为放置到页面的图像获取活动图形状态的合成参数。 |
| [getImage()](#getImage--) | 获取相关的 XImage 资源对象。 |
| [getMatrix()](#getMatrix--) | 此图像的当前变换矩阵。 |
| [getOperator()](#getOperator--) | 用于显示图像的运算符。 |
| [getPage()](#getPage--) | 获取包含图像的页面。 |
| [getRectangle()](#getRectangle--) | 获取图像的矩形。 |
| [getResolution()](#getResolution--) | 获取图像的分辨率。 |
| [getRotation()](#getRotation--) | 获取图像的旋转角度。 |
| [hashCode()](#hashCode--) |  |
| [hide()](#hide--) | 从页面中删除图像。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [replace(InputStream image)](#replace-java.io.InputStream-) | 用另一个图像替换集合中的图像。 |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | 保存具有相应变换的图像：缩放、旋转和分辨率。 |
| [save(OutputStream outputStream, ImageType format)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | 保存具有相应变换的图像：缩放、旋转和分辨率。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCompositingParameters() {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```


为放置到页面的图像获取活动图形状态的合成参数。

**退货：**
[CompositingParameters](../../com.aspose.pdf/compositingparameters) - CompositingParameters 对象
### getImage() {#getImage--}
```
public XImage getImage()
```


获取相关的 XImage 资源对象。

**退货：**
[XImage](../../com.aspose.pdf/ximage)-XImage 对象
### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


此图像的当前变换矩阵。

**退货：**
[Matrix](../../com.aspose.pdf/matrix) 矩阵对象
### getOperator() {#getOperator--}
```
public final Operator getOperator()
```


用于显示图像的运算符。

**退货：**
[Operator](../../com.aspose.pdf/operator) 运营商实例
### getPage() {#getPage--}
```
public Page getPage()
```


获取包含图像的页面。

**退货：**
[Page](../../com.aspose.pdf/page) 页面对象
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取图像的矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


获取图像的分辨率。

**退货：**
[Resolution](../../com.aspose.pdf.devices/resolution) 解析对象
### getRotation() {#getRotation--}
```
public float getRotation()
```


获取图像的旋转角度。

**退货：**
浮点数 - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### hide() {#hide--}
```
public final void hide()
```


从页面中删除图像。

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### replace(InputStream image) {#replace-java.io.InputStream-}
```
public void replace(InputStream image)
```


用另一个图像替换集合中的图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.io.InputStream | 包含图像数据的流。 |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


保存具有相应变换的图像：缩放、旋转和分辨率。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 将保存图像的流 |

### save(OutputStream outputStream, ImageType format) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void save(OutputStream outputStream, ImageType format)
```


保存具有相应变换的图像：缩放、旋转和分辨率。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 将保存图像的流 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 将用于图像编码的格式。图像格式  |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
