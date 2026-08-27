---
title: "PageInformationAnnotation"
linktitle: "PageInformationAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 PDF 文档中的页面信息注释。此注释包含文件名、页码以及注释创建的日期和时间。此类是。"
type: docs
weight: 3380
url: /zh/java/com.aspose.pdf/pageinformationannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.PageInformationAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PageInformationAnnotation extends PrinterMarkAnnotation
```

表示 PDF 文档中的 Page Information 注释。此注释包含文件名、页码以及注释创建的日期和时间。此类主要用于向 PDF 文档的特定页面添加元数据，这对于跟踪和引用非常有用。例如，可在打印过程中标记页面，或在查看文档时提供关于页面的额外信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageInformationAnnotation](#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 在给定页面的指定位置初始化 {@link PageInformationAnnotation} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受用于注释处理的访问者。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |

### PageInformationAnnotation {#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
在给定页面的指定位置初始化 {@link PageInformationAnnotation} 类的新实例。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受用于注释处理的访问者。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
int 值
