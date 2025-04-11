---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptions 类。表示文本替换选项
type: docs
weight: 11010
url: /zh/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions 类

表示文本替换选项

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | 初始化 `TextReplaceOptions` 对象的新实例，用于指定的替换后操作。 |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | 初始化 `TextReplaceOptions` 对象的新实例，用于指定的范围。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | 获取或设置在强制创建新文本行时使用的行间距值。期望的值是替换文本的字体大小的倍数。默认值为 1.2。 |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | 获取或设置一个值，指示在文本替换后调整页面上的文本时是否忽略不同的段落。 |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | 设置或获取使用 TextReplaceOptions 时替换文本的左侧位置调整：- ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | 获取或设置在替换文本片段为更短文本后将执行的操作。 |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | 获取或设置替换文本操作应用的范围 |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | 设置或获取使用 TextReplaceOptions 时替换文本的右侧位置调整：- ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### 另请参阅

* 类 [TextOptions](../textoptions/)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)