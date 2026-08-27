---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示包含动画图形和声音的电影注释，这些内容将在电脑屏幕和扬声器上呈现。当注释被激活时，"
type: docs
weight: 3090
url: /zh/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

表示包含动画图形和声音的电影注释，可在计算机屏幕上和扬声器中呈现。当注释被激活时，电影将播放。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | 用于 Generator 的构造函数。 |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | 在指定页面上创建新的 Sound 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getAspect](#getAspect--) | 获取或设置电影边界框的宽度和高度（单位为像素）。 |
| [getFile](#getFile--) | 获取标识自描述电影文件的文件规范。 |
| [getPoster](#getPoster--) | 获取或设置标志或流，以指定是否以及如何显示代表电影的海报图像。如果为 true，则从电影文件中检索海报图像；如果为 false，则不显示海报。 |
| [getRotate](#getRotate--) | 获取或设置电影相对于页面顺时针旋转的角度数。该值必须是 90 的倍数。 |
| [getTitle](#getTitle--) | 获取电影注释的标题。 |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | 获取或设置电影边界框的宽度和高度（单位为像素）。 |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | 设置标识自描述电影文件的文件规范。 |
| [setPoster](#setPoster-boolean-) | 获取或设置标志或流，以指定是否以及如何显示代表电影的海报图像。如果为 true，则从电影文件中检索海报图像；如果为 false，则不显示海报。 |
| [setRotate](#setRotate-int-) | 获取或设置电影相对于页面顺时针旋转的角度数。该值必须是 90 的倍数。 |
| [setTitle](#setTitle-java.lang.String-) | 设置电影注释的标题。 |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
用于 Generator 的构造函数。

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
在指定页面上创建新的 Sound 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素作为 int 值 @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

获取或设置电影边界框的宽度和高度（单位为像素）。

**Returns:**
Point 实例

### getFile {#getFile--}
```
public FileSpecification getFile()
```

获取标识自描述电影文件的文件规范。

**Returns:**
FileSpecification 值

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

获取或设置标志或流，以指定是否以及如何显示代表电影的海报图像。如果为 true，则从电影文件中检索海报图像；如果为 false，则不显示海报。

**Returns:**
布尔值

### getRotate {#getRotate--}
```
public final int getRotate()
```

获取或设置电影相对于页面顺时针旋转的角度数。该值必须是 90 的倍数。

**Returns:**
int 值

### getTitle {#getTitle--}
```
public String getTitle()
```

获取电影注释的标题。

**Returns:**
字符串值

### setAspect {#setAspect-com.aspose.pdf.Point-}
获取或设置电影边界框的宽度和高度（单位为像素）。

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
设置标识自描述电影文件的文件规范。

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

获取或设置标志或流，以指定是否以及如何显示代表电影的海报图像。如果为 true，则从电影文件中检索海报图像；如果为 false，则不显示海报。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

获取或设置电影相对于页面顺时针旋转的角度数。该值必须是 90 的倍数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setTitle {#setTitle-java.lang.String-}
设置电影注释的标题。
