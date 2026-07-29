---
title: "GraphicalPdfComparer.ComparePagesToImage"
second_title: "Aspose.PDF for .NET API 参考"
description: "GraphicalPdfComparer 方法。以图形方式比较页面。比较结果放置在图像中。"
type: docs
weight: 70
url: /zh/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## GraphicalPdfComparer.ComparePagesToImage method

以图形方式比较页面。比较结果放置在图像中。

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page1 | 页面 | 要比较的第一页。 |
| page2 | 页面 | 要比较的第二页。 |
| resultImagePath | String | 目标图像文件的路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果被比较的页面尺寸不同。如果 resultImagePath 为 null 或空字符串。保存图像格式未知。 |

### 另请参见

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


