---
title: Enum TextFormattingOptions.WordWrapMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFormattingOptionsWordWrapMode 枚举。定义单词换行策略
type: docs
weight: 10930
url: /zh/net/aspose.pdf.text/textformattingoptions.wordwrapmode/
---
## TextFormattingOptions.WordWrapMode 枚举

定义单词换行策略

```csharp
public enum WordWrapMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NoWrap | `0` | 不执行换行 |
| DiscretionaryHyphenation | `1` | 执行自愿连字符。允许在单词中间断开。 |
| ByWords | `2` | 单词换行仅在完整单词上进行。如果完整单词无法换行，则尝试使用自愿连字符 |
| Undefined | `3` | 未设置 WordWrapMode。将使用上层结构（表格单元格、段落等）的换行策略。 |

### 另请参阅

* class [TextFormattingOptions](../textformattingoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)