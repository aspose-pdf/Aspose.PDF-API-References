---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF for Java API 参考"
description: "注意！该功能已实现，但由于在 OSHARED 层发现的阻塞问题尚未放入公共 API。表示页面大小的使用模式。"
type: docs
weight: 2810
url: /zh/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

注意！该功能已实现，但由于在 OSHARED 层发现的阻塞问题尚未公开到 API。表示转换过程中页面尺寸的使用模式。诸如 HTML、EPUB 等格式通常采用浮动布局，因此可以适配所需的页面尺寸。但有时内容指定了水平位置或尺寸，导致无法放入所需的页面尺寸。在这种情况下，我们可以定义应如何处理（即当内容尺寸不符合结果 PDF 文档的初始页面尺寸时）。

## 字段

| 字段 | 描述 |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | 此模式定义了如下行为：在获取转换结果后，检测到部分内容被截断时，视口宽度会扩大以适应内容并重新进行转换。该模式在这种情况下可以得到更少的结果页，但需要重复渲染（因此会增加处理时间）。 |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | 在此模式下，结果页将使用 LoadOptions 中定义的所需页面尺寸，无论转换后的内容是否超出页面边界。 |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

此模式定义了如下行为：在获取转换结果后，检测到部分内容被截断时，视口宽度会扩大以适应内容并重新进行转换。该模式在这种情况下可以得到更少的结果页，但需要重复渲染（因此会增加处理时间）。

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

在此模式下，结果页将使用 LoadOptions 中定义的所需页面尺寸，无论转换后的内容是否超出页面边界。
