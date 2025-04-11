---
title: GraphicalPdfComparer.CompareDocumentsToPdf
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer 方法。以图形方式比较文档。比较结果放置在 PDF 文档中
type: docs
weight: 60
url: /zh/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## GraphicalPdfComparer.CompareDocumentsToPdf 方法

以图形方式比较文档。比较结果放置在 PDF 文档中。

```csharp
public void CompareDocumentsToPdf(Document document1, Document document2, string resultPdfPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document1 | Document | 第一个要比较的文档。 |
| document2 | Document | 第二个要比较的文档。 |
| resultPdfPath | String | 目标 PDF 文件路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果被比较的页面大小不同。如果 resultPdfPath 为 null 或空字符串。 |

### 另请参见

* 类 [Document](../../../aspose.pdf/document/)
* 类 [GraphicalPdfComparer](../)
* 命名空间 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* 程序集 [Aspose.PDF](../../../)