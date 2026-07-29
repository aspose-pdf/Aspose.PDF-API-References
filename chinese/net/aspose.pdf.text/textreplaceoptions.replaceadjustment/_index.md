---
title: "枚举 TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment 枚举。确定在将文本片段替换为更短后将执行的操作。None —— 不执行操作，替换后的文本可能会覆盖行的其余部分。AdjustSpaceWidth —— 尝试调整单词之间的空格以保持行长度。WholeWordsHyphenation —— 尝试在段落行之间分配单词以保持段落的右侧对齐。ShiftRestOfLine —— 根据文本长度的变化移动行的其余部分，行的长度可能会改变。默认值为 ShiftRestOfLine。"
type: docs
weight: 11210
url: /zh/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

确定在将文本片段替换为更短后将执行的操作。None - 不执行操作，替换后的文本可能会覆盖行的其余部分；AdjustSpaceWidth - 尝试调整单词之间的空格以保持行长度；WholeWordsHyphenation - 尝试在段落行之间分配单词以保持段落的右侧对齐；ShiftRestOfLine - 根据文本长度的变化移动行的其余部分，行的长度可能会改变；默认值为 ShiftRestOfLine。

```csharp
[Flags]
public enum ReplaceAdjustment
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 不执行操作，替换后的文本可能会覆盖行的其余部分 |
| AdjustSpaceWidth | `1` | 尝试调整单词之间的空格以保持行长度 |
| WholeWordsHyphenation | `2` | 尝试在段落行之间分配单词以保持段落的右侧对齐 |
| IsFormFillingMode | `4` | 尝试使用段落宽度在可用的空白区域中展开单词。如果文本溢出，将被隐藏。 |
| ShiftRestOfLine | `8` | （默认）根据文本长度的变化移动行的其余部分，行的长度可能会改变 |

### 另请参见

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


