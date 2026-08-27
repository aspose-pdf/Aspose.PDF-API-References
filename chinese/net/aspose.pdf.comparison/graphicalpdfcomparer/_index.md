---
title: "类 GraphicalPdfComparer"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Comparison.GraphicalPdfComparer 类。表示用于图形比较 PDF 文档的类。应用于搜索主要是图形性质的细微变化。若要比较文本内容的更改，请使用其他 PDF 比较类"
type: docs
weight: 3300
url: /zh/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

表示用于图形化比较 PDF 文档的类。应用于搜索细微的更改，主要是图形方面的。要比较文本内容的更改，请使用其他 PDF 比较类。

```csharp
public class GraphicalPdfComparer
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | 获取和设置更改标志颜色。默认颜色为红色。 |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | 获取和设置生成图像的分辨率。默认值为 150dpi。 |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | 获取和设置阈值（百分比）。如果更改不显著，此值可让您忽略细微变化。默认值为 0%。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | 以图形方式比较文档。比较结果以图像形式呈现。 |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | 以图形方式比较文档。比较结果放置在 PDF 文档中。 |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | 以图形方式比较页面。比较结果放置在图像中。 |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | 以图形方式比较页面。比较结果放置在 PDF 文档中。 |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | 以图形方式比较页面。比较结果放置在 PDF 文档中。 |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | 获取页面图像之间的差异。结果包含第一页的比较图像以及差异数组。 |

### 另请参见

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


