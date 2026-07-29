---
title: "枚举 LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes 枚举。注意：该功能已实现，但由于在 OSHARED 层的阻塞问题尚未公开 API，针对示例文档。表示在转换期间使用 Page 大小的模式。HTML、EPUB 等格式通常采用浮动布局，因此可以适配所需的 Page 大小。但有时内容指定了水平位置或大小，导致无法放入所需的 Page 大小。在这种情况下，我们可以定义应采取的措施，即当内容大小不符合结果 PDF 文档的初始 Page 大小时的处理方式。"
type: docs
weight: 6280
url: /zh/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

注意！该功能已实现，但由于在 OSHARED 层的阻塞问题尚未公开 API，针对示例文档。表示在转换期间使用 Page 大小的模式。格式（如 HTML、EPUB 等）通常采用浮动设计，因此可以适配所需的 Page 大小。但有时内容指定了水平位置或大小，导致无法放入所需的 Page 大小。在这种情况下，我们可以定义应采取的措施（即当内容大小不符合结果 PDF 文档的初始 Page 大小时）。

```csharp
public enum PageSizeAdjustmentModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | 在此模式下，结果 Page 将使用 LoadOptions 中定义的所需 Page 大小，无论转换后的内容是否超出 Page 边界。 |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | 此模式定义了以下行为：在获取转换结果并检测到部分内容被截断后，视口宽度会扩大以适应内容并重新进行转换。该模式在这种情况下可以得到更少的结果 Page，但需要重复渲染（因此耗时更长）。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


