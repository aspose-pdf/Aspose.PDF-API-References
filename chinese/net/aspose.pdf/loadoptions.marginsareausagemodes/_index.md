---
title: "枚举 LoadOptions.MarginsAreaUsageModes"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.LoadOptionsMarginsAreaUsageModes 枚举。表示在转换期间（如 HTML、EPUB 等）使用页边距区域的模式，定义了对导入格式中与页边距使用相关指令的处理方式。"
type: docs
weight: 6270
url: /zh/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

表示在转换期间（如 HTML、EPUB 等）使用页边距区域的模式，定义了对导入格式中与页边距使用相关指令的处理方式。

```csharp
public enum MarginsAreaUsageModes
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | 在此模式下，转换器遵循导入文档（例如导入的 HTML 的 CSS）在页边距区域的使用方式。因此，如果导入文档的格式要求在渲染时使用页边距区域，转换器将允许这样做。 |
| NeverPutContentOnMarginArea | `1` | 此模式严格禁止使用页边距区域，因此，转换器永远不会在渲染时使用页边距区域，即使 CSS 或源文档的格式允许或要求这样做。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


