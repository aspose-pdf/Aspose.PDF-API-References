---
title: "类 TextReplaceOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextReplaceOptions 类。表示文本替换选项"
type: docs
weight: 11190
url: /zh/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

表示文本替换选项。

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | 为指定的替换后操作初始化 `TextReplaceOptions` 对象的新实例。 |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | 为指定的范围初始化 `TextReplaceOptions` 对象的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | 获取或设置行间距的值，该值在强制替换调整以创建新文本行时使用。期望的值是被替换文本字体大小的倍数。默认值为 1.2。 |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | 获取或设置调整字体大小以适应由 [`Rectangle`](./rectangle/) 定义的边界的策略。 |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | 获取或设置一个值，指示在文本替换后调整页面文本时是否忽略不同的段落。 |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | 设置或获取使用 TextReplaceOptions 时替换文本的左侧位置调整：- ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | 获取或设置用于容纳替换后文本的矩形。 |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | 获取或设置在文本片段替换后将执行的更短的操作。 |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | 获取或设置应用文本替换操作的范围 |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | 设置或获取使用 TextReplaceOptions 时替换文本的右侧位置调整：- ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### 另请参见

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


