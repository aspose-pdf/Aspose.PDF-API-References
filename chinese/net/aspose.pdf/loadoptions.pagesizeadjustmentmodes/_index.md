---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes 枚举。注意：该功能已实现，但由于在样本文档中发现的 OSHARED 层的阻塞问题尚未公开 API。表示在转换过程中使用页面大小的模式。像 HTML、EPUB 等格式通常具有浮动设计，因此可以适应所需的页面大小。但有时内容具有特定的水平位置或大小，无法将内容放入所需的页面大小。在这种情况下，我们可以定义在这种情况下应该采取的措施，即当内容的大小不符合结果 PDF 文档的初始页面大小时。
type: docs
weight: 6140
url: /zh/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes 枚举

注意！该功能已实现，但由于在样本文档中发现的 OSHARED 层的阻塞问题尚未公开 API。表示在转换过程中使用页面大小的模式。格式（如 HTML、EPUB 等）通常具有浮动设计，因此可以适应所需的页面大小。但有时内容具有特定的水平位置或大小，无法将内容放入所需的页面大小。在这种情况下，我们可以定义在这种情况下应该采取的措施（即当内容的大小不符合结果 PDF 文档的初始页面大小时）。

```csharp
public enum PageSizeAdjustmentModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | 在此模式下，结果页面将具有 LoadOptions 中定义的所需页面大小，无论转换后的内容是否超出页面边界。 |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | 此模式定义了这样的行为：在获取转换结果并检测到某些内容被截断后，视口的宽度被扩大以适应内容，并重复转换。在这种情况下，此模式允许获得更少的结果页面，但需要重复渲染（因此需要更多的处理时间）。 |

### 另请参阅

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)