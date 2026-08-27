---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "类 PDF3DAnnotation。此类不可继承。@see Annotation"
type: docs
weight: 3560
url: /zh/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

类 PDF3DAnnotation。此类不可继承。@see Annotation

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | 初始化 {@code PDF3DAnnotation} 类的新实例。 |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | 初始化 {@code PDF3DAnnotation} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受用于注释处理的访问者。 |
| [clearImagePreview](#clearImagePreview--) | 清除图像预览。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释的类型。值：注释的类型。 |
| [getContent](#getContent--) | 获取或设置内容。值：内容。 |
| [getImagePreview](#getImagePreview--) | 获取图像预览。 |
| [getLightingScheme](#getLightingScheme--) | 获取光照方案。值：光照方案。 |
| [getPdf3DArtwork](#getPdf3DArtwork--) | 获取 3D 艺术作品。值：PDF3 d artwork。 |
| [getRenderMode](#getRenderMode--) | 获取渲染模式。值：渲染模式。 |
| [getViewArray](#getViewArray--) | 获取视图数组。值：视图数组。 |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | 获取或设置内容。值：内容。 |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | 设置默认视图的索引。 |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | 设置图像预览。 |
| [setImagePreview](#setImagePreview-java.lang.String-) | 设置图像预览。 |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
初始化 {@code PDF3DAnnotation} 类的新实例。

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
初始化 {@code PDF3DAnnotation} 类的新实例。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受用于注释处理的访问者。

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

清除图像预览。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释的类型。值：注释的类型。

**Returns:**
int 值

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

获取或设置内容。值：内容。

**Returns:**
PDF3DContent object

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

获取图像预览。

**Returns:**
图像预览为流。

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

获取光照方案。值：光照方案。

**Returns:**
PDF3DLightingScheme object

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

获取 3D 艺术作品。值：PDF3 d artwork。

**Returns:**
PDF3DArtwork object

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

获取渲染模式。值：渲染模式。

**Returns:**
PDF3DRenderMode object

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

获取视图数组。值：视图数组。

**Returns:**
PDF3DViewArray object

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
获取或设置内容。值：内容。

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

设置默认视图的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 默认视图索引。 |

### setImagePreview {#setImagePreview-java.io.InputStream-}
设置图像预览。

### setImagePreview {#setImagePreview-java.lang.String-}
设置图像预览。
