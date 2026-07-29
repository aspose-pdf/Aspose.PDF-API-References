---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示橡皮图章注释。此类注释显示的文本或图形旨在看起来像是用橡皮图章盖在页面上。 </p> <hr>."
type: docs
weight: 4630
url: /zh/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> 表示橡胶印章注释。此类注释显示旨在看起来像用橡胶印章盖在页面上的文本或图形。 </p> <hr> <pre> 以下代码片段演示如何在第一个 PDF 文档页中添加 2 个印章。输入文档来自 inFile，修改后保存到 outFile。第一个印章使用图标 NotForPublicRelease，第二个使用来自 rubber.jpg 的图像。 Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream(\"rubber.jpg\", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | 构造函数 |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 在指定页面上创建新的 Stamp 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受 {@code AnnotationSelector} 访问者在浏览注释集合时。 |
| [clear](#clear--) | 清除静态实例 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getIcon](#getIcon--) | 获取橡皮图章的图标。 |
| [getImage](#getImage--) | 获取注释的图像。 |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | 以 Base64 字符串设置注释的 SVG 图像。 |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | 设置橡皮图章的图标。 |
| [setImage](#setImage-java.io.InputStream-) | 设置注释的图像。 |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
构造函数

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
在指定页面上创建新的 Stamp 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受 {@code AnnotationSelector} 访问者在浏览注释集合时。

### clear {#clear--}
```
public static void clear()
```

清除静态实例

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

获取橡皮图章的图标。

**Returns:**
StampIcon 值

### getImage {#getImage--}
```
public InputStream getImage()
```

获取注释的图像。

**Returns:**
InputStream 对象

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
以 Base64 字符串设置注释的 SVG 图像。

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
设置橡皮图章的图标。

### setImage {#setImage-java.io.InputStream-}
设置注释的图像。
