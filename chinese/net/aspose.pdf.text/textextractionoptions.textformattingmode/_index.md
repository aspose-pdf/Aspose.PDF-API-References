---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode 枚举。定义在将 pdf 文档转换为文本时可以使用的不同模式。请参见 TextDevice 类
type: docs
weight: 10900
url: /zh/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode 枚举

定义在将 pdf 文档转换为文本时可以使用的不同模式。请参见 !:TextDevice 类。

```csharp
public enum TextFormattingMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Pure | `0` | 以一定的格式化例程表示 pdf 内容。 |
| Raw | `1` | 原样表示 pdf 内容，即不进行格式化。 |
| Flatten | `2` | 通过其坐标定位文本片段来表示 pdf 内容。基本上类似于“Raw”模式。但“Raw”侧重于保留文档中文本片段（操作符）的结构，而“Flatten”侧重于保持文本的阅读顺序。 |
| MemorySaving | `3` | 进行内存节省的提取。几乎与“Raw”模式相同，但运行稍快且使用更少的内存。 |

### 另请参阅

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)