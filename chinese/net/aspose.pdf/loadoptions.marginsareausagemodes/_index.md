---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes 枚举。表示在转换过程中使用边距区域的模式，如 HTML EPUB 等，定义与使用边距相关的导入格式指令的处理。
type: docs
weight: 6130
url: /zh/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes 枚举

表示在转换过程中使用边距区域的模式（如 HTML、EPUB 等），定义与使用边距相关的导入格式指令的处理。

```csharp
public enum MarginsAreaUsageModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | 在此模式下，转换器遵循导入文档的格式（例如，导入 HTML 的 CSS）在使用边距区域时。因此，如果导入文档的格式要求使用边距区域进行渲染，转换器将允许这样做。 |
| NeverPutContentOnMarginArea | `1` | 此模式严格禁止使用边距区域，因此，转换器将永远不会使用边距区域进行渲染，即使 CSS 或源文档的格式允许或要求这样做。 |

### 另请参阅

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)