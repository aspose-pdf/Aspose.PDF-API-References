---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment 枚举。确定在替换文本片段为更短文本后将执行的操作。None - 无操作，替换的文本可能会与行的其余部分重叠；AdjustSpaceWidth - 尝试调整单词之间的空格以保持行长度；WholeWordsHyphenation - 尝试在段落行之间分配单词以保持段落的正确字段；ShiftRestOfLine - 根据文本长度的变化移动行的其余部分，行的长度可能会改变；默认值为 ShiftRestOfLine。
type: docs
weight: 11020
url: /zh/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment 枚举

确定在替换文本片段为更短文本后将执行的操作。None - 无操作，替换的文本可能会与行的其余部分重叠；AdjustSpaceWidth - 尝试调整单词之间的空格以保持行长度；WholeWordsHyphenation - 尝试在段落行之间分配单词以保持段落的正确字段；ShiftRestOfLine - 根据文本长度的变化移动行的其余部分，行的长度可能会改变；默认值为 ShiftRestOfLine。

```csharp
[Flags]
public enum ReplaceAdjustment
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 无操作，替换的文本可能会与行的其余部分重叠 |
| AdjustSpaceWidth | `1` | 尝试调整单词之间的空格以保持行长度 |
| WholeWordsHyphenation | `2` | 尝试在段落行之间分配单词以保持段落的正确字段 |
| IsFormFillingMode | `4` | 尝试在可用的空白区域内使用段落宽度分散单词。如果文本溢出，将被隐藏。 |
| ShiftRestOfLine | `8` | （默认）根据文本长度的变化移动行的其余部分，行的长度可能会改变 |

### 另请参阅

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)