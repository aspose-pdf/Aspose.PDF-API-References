---
title: ImagePlacementAbsorber
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示图像放置对象的吸收器对象。
type: docs
weight: 172
url: /zh/java/com.aspose.pdf/imageplacementabsorber/
---
**遗产：**
java.lang.Object
```
public final class ImagePlacementAbsorber
```

表示图像放置对象的吸收器对象。执行图像用法搜索并通过 ImagePlacementAbsorber.ImagePlacements 集合提供对搜索结果的访问。

--------------------

```
The example demonstrates how to find images on the first PDF document page and get the image placement properties.


 //打开文档
 Document doc = new Document("D:\\Tests\\input.pdf");
 //创建 ImagePlacementAbsorber 对象以执行图像放置搜索
 ImagePlacementAbsorber abs = new ImagePlacementAbsorber();
 //接受第一页的吸收器
 doc.getPages().get_Item(1).accept(abs);
 //显示所有展示位置的图片展示位置属性
 for (ImagePlacement imagePlacement : ```
(Iterable)
```abs.getImagePlacements())
 {
     System.out.println("image width:" + imagePlacement.getRectangle().getWidth());
     System.out.println("image height:" + imagePlacement.getRectangle().getHeight());
     System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX());
     System.out.println("image LLY:" + imagePlacement.getRectangle.getY());
     System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX());
     System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY());
 }
```

--------------------

ImagePlacementAbsorber 对象主要用于图像搜索场景。搜索完成后，出现的事件用 ImagePlacementAbsorber.ImagePlacements 集合包含的 ImagePlacement 对象表示。 ImagePlacement 对象提供对图像放置属性的访问：尺寸、分辨率等。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImagePlacementAbsorber()](#ImagePlacementAbsorber--) | 初始化 ImagePlacementAbsorber 对象的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getImagePlacements()](#getImagePlacements--) | 获取与 ImagePlacement 对象一起出现的图像放置事件的集合。 |
| [hashCode()](#hashCode--) |  |
| [isReadOnlyMode()](#isReadOnlyMode--) | 获取/设置解析操作集合的只读模式。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | 获取/设置解析操作集合的只读模式。 |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | 对指定文档执行搜索。 |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | 在指定页面上执行搜索。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImagePlacementAbsorber() {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```


初始化 ImagePlacementAbsorber 对象的新实例。

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
### getImagePlacements() {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```


获取与 ImagePlacement 对象一起出现的图像放置事件的集合。

**退货：**
[ImagePlacementCollection](../../com.aspose.pdf/imageplacementcollection) - ImagePlacementCollection 对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isReadOnlyMode() {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```


获取/设置解析操作集合的只读模式。它可能有助于防止内存不足异常。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


获取/设置解析操作集合的只读模式。它可能有助于防止内存不足异常。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


对指定文档执行搜索。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | Pdf 文档对象。 |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


在指定页面上执行搜索。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf 文档页面对象。 |

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
