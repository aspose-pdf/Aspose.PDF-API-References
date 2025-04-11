---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.GraphicalPdfComparer class. 表示一个用于图形比较 PDF 文档的类。应主要用于搜索小的变化，主要是图形性质的变化。要比较文本内容的变化，请使用其他 PDF 比较类。
type: docs
weight: 3190
url: /zh/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

表示一个用于图形比较 PDF 文档的类。应主要用于搜索小的变化，主要是图形性质的变化。要比较文本内容的变化，请使用其他 PDF 比较类。

```csharp
public class GraphicalPdfComparer
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | 获取和设置变化标记颜色。默认颜色为红色。 |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | 获取和设置生成图像的分辨率。默认值为 150dpi。 |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | 获取和设置阈值百分比。此值允许您忽略不显著的小变化。默认值为 0%。 |

## Methods

| Name | Description |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | 以图形方式比较文档。比较结果放置在图像中。 |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | 以图形方式比较文档。比较结果放置在 PDF 文档中。 |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | 以图形方式比较页面。比较结果放置在图像中。 |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | 以图形方式比较页面。比较结果放置在 PDF 文档中。 |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | 以图形方式比较页面。比较结果放置在 PDF 文档中。 |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | 获取页面图像之间的差异。结果包含第一个比较页面的图像和差异数组。 |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)