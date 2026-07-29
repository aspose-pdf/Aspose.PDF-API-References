---
title: "枚举 TextExtractionOptions.TextFormattingMode"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode 枚举。定义在将 pdf 文档转换为文本时可使用的不同模式。参见 TextDevice 类"
type: docs
weight: 11080
url: /zh/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

定义在将 pdf 文档转换为文本时可使用的不同模式。参见 TextDevice 类。

```csharp
public enum TextFormattingMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Pure | `0` | 以少量格式化例程表示 pdf 内容。 |
| Raw | `1` | 原样表示 pdf 内容，即不进行格式化。 |
| Flatten | `2` | 通过坐标定位文本片段来表示 pdf 内容。这基本上类似于 “Raw” 模式。但 “Raw” 侧重于保留文档中文本片段（运算符）的结构，而 “Flatten” 则侧重于保持文本的阅读顺序。 |
| MemorySaving | `3` | 节省内存的提取方式。它几乎与 “Raw” 模式相同，但运行稍快且占用更少的内存。 |

### 另请参见

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


