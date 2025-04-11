---
title: GraphicalPdfComparer.GetDifference
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer 方法。获取页面图像之间的差异。结果包含比较的第一页的图像和一个差异数组。
type: docs
weight: 90
url: /zh/net/aspose.pdf.comparison/graphicalpdfcomparer/getdifference/
---
## GraphicalPdfComparer.GetDifference 方法

获取页面图像之间的差异。结果包含比较的第一页的图像和一个差异数组。

```csharp
public ImagesDifference GetDifference(Page page1, Page page2)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page1 | Page | 第一页。 |
| page2 | Page | 第二页。 |

### 返回值

[`ImagesDifference`](../../imagesdifference/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果被比较的页面大小不同。 |

### 另请参阅

* 类 [ImagesDifference](../../imagesdifference/)
* 类 [Page](../../../aspose.pdf/page/)
* 类 [GraphicalPdfComparer](../)
* 命名空间 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* 程序集 [Aspose.PDF](../../../)