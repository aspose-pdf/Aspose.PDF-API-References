---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于图形比较 PDF 文档的类。应用于搜索小幅度的更改，主要是图形方面的。若要比较文本内容的更改，请使用其他方法。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

表示用于图形比较 PDF 文档的类。应用于搜索小幅度的更改，主要是图形方面的更改。若要比较文本内容的更改，请使用其他 PDF 比较类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | 创建 {@link GraphicalPdfComparer} 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | 对文档进行图形比较。 |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | 对文档进行图形比较。比较结果放置在 PDF 文档中。 |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | 对页面进行图形比较。比较结果放置在图像中。 |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | 对页面进行图形比较。比较结果放置在 PDF 文档中。 |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | 对页面进行图形比较。比较结果放置在 PDF 文档中。 |
| [getColor](#getColor--) | 获取并设置更改标记颜色。默认颜色为红色。 |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | 获取页面图像之间的差异。结果包含比较后的第一页图像以及差异数组。 |
| [getResolution](#getResolution--) | 获取并设置生成图像的分辨率。默认值为 150dpi。 |
| [getThreshold](#getThreshold--) | 获取和设置阈值（百分比）。该值允许您在变化不显著时忽略微小的变化。默认值为 0%。 |
| [setColor](#setColor-com.aspose.pdf.Color-) | 获取并设置更改标记颜色。默认颜色为红色。 |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | 获取并设置生成图像的分辨率。默认值为 150dpi。 |
| [setThreshold](#setThreshold-double-) | 获取和设置阈值（百分比）。该值允许您在变化不显著时忽略微小的变化。默认值为 0%。 |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

创建 {@link GraphicalPdfComparer} 类的实例。

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
对文档进行图形比较。

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
对文档进行图形比较。比较结果放置在 PDF 文档中。

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
对页面进行图形比较。比较结果放置在图像中。

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
对页面进行图形比较。比较结果放置在 PDF 文档中。

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
对页面进行图形比较。比较结果放置在 PDF 文档中。

### getColor {#getColor--}
```
public final Color getColor()
```

获取并设置更改标记颜色。默认颜色为红色。

**Returns:**
Color 实例

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
获取页面图像之间的差异。结果包含比较后的第一页图像以及差异数组。

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

获取并设置生成图像的分辨率。默认值为 150dpi。

**Returns:**
Resolution 实例

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

获取和设置阈值（百分比）。该值允许您在变化不显著时忽略微小的变化。默认值为 0%。

**Returns:**
double 值

### setColor {#setColor-com.aspose.pdf.Color-}
获取并设置更改标记颜色。默认颜色为红色。

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
获取并设置生成图像的分辨率。默认值为 150dpi。

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

获取和设置阈值（百分比）。该值允许您在变化不显著时忽略微小的变化。默认值为 0%。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |
