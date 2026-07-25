---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Aspose.PDF for Java API 参考"
description: "表示转换过程中页边距区域的使用模式（如 HTML、EPUB 等），定义对导入格式中与页边距使用相关指令的处理。"
type: docs
weight: 2800
url: /zh/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

表示转换过程中页边距区域的使用模式（如 HTML、EPUB 等），定义对导入格式中与页边距使用相关指令的处理。

## 字段

| 字段 | 描述 |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | 此模式严格禁止使用页边距区域，因此，即使 CSS 或源文档的格式允许或要求，转换器也永远不会在渲染时使用页边距区域。 |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | 在此模式下，转换器遵循导入文档的格式（例如导入的 HTML 的 CSS）来使用页边距区域。因此，如果导入文档的格式要求在渲染时使用页边距区域，转换器将允许这样做。 |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

此模式严格禁止使用页边距区域，因此，即使 CSS 或源文档的格式允许或要求，转换器也永远不会在渲染时使用页边距区域。

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

在此模式下，转换器遵循导入文档的格式（例如导入的 HTML 的 CSS）来使用页边距区域。因此，如果导入文档的格式要求在渲染时使用页边距区域，转换器将允许这样做。
