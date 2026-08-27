---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示图像放置对象的吸收器对象。执行图像使用情况的搜索，并通过 {@code 提供对搜索结果的访问。"
type: docs
weight: 2340
url: /zh/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> 表示图像放置对象的吸收器对象。执行图像使用情况的搜索，并通过 {@code ImagePlacementAbsorber.ImagePlacements} 集合提供对搜索结果的访问。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上查找图像并获取图像放置属性。 // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println(\"image width:\" + imagePlacement.getRectangle().getWidth()); System.out.println(\"image height:\" + imagePlacement.getRectangle().getHeight()); System.out.println(\"image LLX:\" + imagePlacement.getRectangle(0).getX()); System.out.println(\"image LLY:\" + imagePlacement.getRectangle.getY()); System.out.println(\"image horizontal resolution:\" + imagePlacement.getResolution().getX()); System.out.println(\"image vertical resolution:\" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> {@code ImagePlacementAbsorber} 对象主要用于图像搜索场景。搜索完成后，出现的实例以 {@code ImagePlacement} 对象表示，这些对象包含在 {@code ImagePlacementAbsorber.ImagePlacements} 集合中。{@code ImagePlacement} 对象提供对图像放置属性的访问：尺寸、分辨率等。 </p> 图像的正向旋转为逆时针，而页面的正向旋转为顺时针。在此，我们需要表示图像的旋转角度，因此需要从图像角度中减去页面角度。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | 初始化 {@code ImagePlacementAbsorber} 对象的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | 获取以 {@code ImagePlacement} 对象呈现的图像放置出现的集合。 |
| [isReadOnlyMode](#isReadOnlyMode--) | 获取/设置解析操作集合的只读模式。这可能有助于防止内存不足异常。 |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | 获取/设置解析操作集合的只读模式。这可能有助于防止内存不足异常。 |
| [visit](#visit-com.aspose.pdf.IDocument-) | 在指定的文档上执行搜索。 |
| [visit](#visit-com.aspose.pdf.Page-) | 在指定页面上执行搜索。 |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

初始化 {@code ImagePlacementAbsorber} 对象的新实例。

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

获取以 {@code ImagePlacement} 对象呈现的图像放置出现的集合。

**Returns:**
ImagePlacementCollection 对象

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

获取/设置解析操作集合的只读模式。这可能有助于防止内存不足异常。

**Returns:**
布尔值

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

获取/设置解析操作集合的只读模式。这可能有助于防止内存不足异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### visit {#visit-com.aspose.pdf.IDocument-}
在指定的文档上执行搜索。

### visit {#visit-com.aspose.pdf.Page-}
在指定页面上执行搜索。
