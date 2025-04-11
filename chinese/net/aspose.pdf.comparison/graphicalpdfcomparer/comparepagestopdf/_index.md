---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer 方法。以图形方式比较页面。比较结果放置在 PDF 文档中
type: docs
weight: 80
url: /zh/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

以图形方式比较页面。比较结果放置在 PDF 文档中。

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page1 | Page | 第一个页面。 |
| page2 | Page | 第二个页面。 |
| resultPdfPath | String | 目标 PDF 文件的路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果被比较的页面大小不同。如果 resultPdfPath 为 null 或空字符串。 |

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

以图形方式比较页面。比较结果放置在 PDF 文档中。

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page1 | Page | 第一个页面。 |
| page2 | Page | 第二个页面。 |
| pdfDocument | Document | PDF 文档实例。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果被比较的页面大小不同。 |

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)