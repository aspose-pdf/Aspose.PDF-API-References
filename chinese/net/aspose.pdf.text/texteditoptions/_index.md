---
title: TextEditOptions
second_title: Aspose.PDF for .NET API 参考
description: 描述文本编辑操作的选项
type: docs
weight: 6980
url: /zh/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

描述文本编辑操作的选项。

```csharp
public sealed class TextEditOptions : TextOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TextEditOptions](texteditoptions#constructor)(bool) | 初始化[`TextEditOptions`](../texteditoptions)指定语言转换权限的对象。 |
| [TextEditOptions](texteditoptions#constructor_1)(FontReplace) | 初始化[`TextEditOptions`](../texteditoptions)指定字体替换行为模式的对象。 |
| [TextEditOptions](texteditoptions#constructor_2)(LanguageTransformation) | 初始化[`TextEditOptions`](../texteditoptions)对象为指定的语言转换行为模式。 |
| [TextEditOptions](texteditoptions#constructor_3)(NoCharacterAction) | 初始化[`TextEditOptions`](../texteditoptions)指定无字符行为模式的对象。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation) { get; set; } | 获取或设置允许在添加或编辑文本期间使用语言转换的值。 true - 如有必要，将应用语言转换（默认值）。 false - 不应用语言转换。 |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing) { get; set; } | 获取编辑文本的剪切路径处理模式。 |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior) { get; set; } | 获取定义字体替换方案行为的模式。 |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior) { get; set; } | 获取定义语言转换场景行为的模式。 |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior) { get; set; } | 获取或设置在字体不包含请求的字符时定义行为的模式。 |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont) { get; set; } | 如果用户字体不包含所需的字符，则获取或设置用于替换的字体 |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource) { get; set; } | 获取或设置允许在源文档页面上搜索文本下划线的值。 （已过时）请使用 TextSearchOptions.SearchForTextRelatedGraphics 代替 this. |

### 也可以看看

* class [TextOptions](../textoptions)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->