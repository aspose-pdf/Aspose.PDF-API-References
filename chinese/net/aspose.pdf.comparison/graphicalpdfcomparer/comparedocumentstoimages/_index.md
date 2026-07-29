---
title: "GraphicalPdfComparer.CompareDocumentsToImages"
second_title: "Aspose.PDF for .NET API 参考"
description: "GraphicalPdfComparer 方法。以图形方式比较文档。比较结果放置在图像中。"
type: docs
weight: 50
url: /zh/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages method

以图形方式比较文档。比较结果以图像形式呈现。

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document1 | Document | 要比较的第一个文档。 |
| document2 | Document | 要比较的第二个文档。 |
| targetDirectory | String | 用于保存比较结果的目录。 |
| fileNamePrefix | String | 图像名称前缀。 |
| imageFormat | ImageFormat | 要保存的图像格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果被比较的页面尺寸不同。如果 targetDirectory 为 null 或空字符串。如果 fileNamePrefix 为 null 或空字符串。 |

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


