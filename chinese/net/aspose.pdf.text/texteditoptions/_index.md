---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptions 类。描述文本编辑操作的选项
type: docs
weight: 10820
url: /zh/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

描述文本编辑操作的选项。

```csharp
public sealed class TextEditOptions : TextOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | 初始化 `TextEditOptions` 对象的新实例，用于指定的语言转换权限。 |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | 初始化 `TextEditOptions` 对象的新实例，用于指定的字体替换行为模式。 |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | 初始化 `TextEditOptions` 对象的新实例，用于指定的语言转换行为模式。 |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | 初始化 `TextEditOptions` 对象的新实例，用于指定的无字符行为模式。 |

## Properties

| Name | Description |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | 获取或设置允许在添加或编辑文本时使用语言转换的值。 true - 如果需要，将应用语言转换（默认值）。 false - 不会应用语言转换。 |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | 获取处理编辑文本的剪切路径的模式。 |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | 获取定义字体替换场景行为的模式。 |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | 获取定义语言转换场景行为的模式。 |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | 获取或设置定义在字体不包含请求字符时的行为的模式。 |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | 获取或设置用于替换的字体，如果用户字体不包含所需字符 |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | 获取或设置允许在源文档页面上搜索文本下划线的值。 （已过时）请使用 TextSearchOptions.SearchForTextRelatedGraphics 代替。 |

### See Also

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)