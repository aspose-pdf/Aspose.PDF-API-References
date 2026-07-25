---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示放置在 Pdf 文档页面上的图像的特性。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上查找图像并获取图像。</pre>"
type: docs
weight: 2330
url: /zh/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> 表示放置在 Pdf 文档页面上的图像的特性。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上查找图像并将图像获取为具有可见尺寸的位图。 // 打开文档 Document doc = new Document("D:\\Tests\\input.pdf"); // 创建 ImagePlacementAbsorber 对象以执行图像放置搜索 ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // 接受第一页面的吸收器 doc.getPages().get_Item(1).accept(abs); // 检索具有可见尺寸的图像 for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // 从资源检索图像 imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // 使用实际尺寸创建新位图 scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> 当图像放置到页面时，其尺寸可能与 {@code Resources} 中定义的物理尺寸不同。对象 {@code ImagePlacement} 用于提供此类信息，如尺寸、分辨率等。 </p>

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | 获取放置在页面上的图像所使用的图形状态的合成参数。 |
| [getImage](#getImage--) | 获取相关的 XImage 资源对象。 |
| [getMatrix](#getMatrix--) | 此图像的当前变换矩阵。 |
| [getOperator](#getOperator--) | 用于显示图像的操作符。 |
| [getPage](#getPage--) | 获取包含该图像的页面。 |
| [getRectangle](#getRectangle--) | 获取图像的矩形。 |
| [getResolution](#getResolution--) | 获取图像的分辨率。 |
| [getRotation](#getRotation--) | 获取图像的旋转角度。 |
| [hide](#hide--) | 从页面中删除图像。 |
| [replace](#replace-java.io.InputStream-) | 用另一图像替换集合中的图像。 |
| [save](#save-java.io.OutputStream-) | 保存图像及其相应的变换：缩放、旋转和分辨率。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | 保存图像及其相应的变换：缩放、旋转和分辨率。 |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

获取放置在页面上的图像所使用的图形状态的合成参数。

**Returns:**
CompositingParameters 对象

### getImage {#getImage--}
```
public XImage getImage()
```

获取相关的 XImage 资源对象。

**Returns:**
XImage 对象

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

此图像的当前变换矩阵。

**Returns:**
Matrix 对象

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

用于显示图像的操作符。

**Returns:**
Operator 实例

### getPage {#getPage--}
```
public Page getPage()
```

获取包含该图像的页面。

**Returns:**
Page 对象

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取图像的矩形。

**Returns:**
Rectangle 对象

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

获取图像的分辨率。

**Returns:**
Resolution 对象

### getRotation {#getRotation--}
```
public float getRotation()
```

获取图像的旋转角度。

**Returns:**
int 值

### hide {#hide--}
```
public final void hide()
```

从页面中删除图像。

### replace {#replace-java.io.InputStream-}
用另一图像替换集合中的图像。

### save {#save-java.io.OutputStream-}
保存图像及其相应的变换：缩放、旋转和分辨率。

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
保存图像及其相应的变换：缩放、旋转和分辨率。
