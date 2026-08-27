---
title: "类 TextEditOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextEditOptions 类。描述文本编辑操作的选项。"
type: docs
weight: 11000
url: /zh/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class

描述文本编辑操作的选项。

```csharp
public sealed class TextEditOptions : TextOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | 为指定的语言转换权限初始化 `TextEditOptions` 对象的新实例。 |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | 为指定的字体替换行为模式初始化 `TextEditOptions` 对象的新实例。 |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | 为指定的语言转换行为模式初始化 `TextEditOptions` 对象的新实例。 |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | 为指定的无字符行为模式初始化 `TextEditOptions` 对象的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | 获取或设置在添加或编辑文本时是否允许使用语言转换的值。true - 如有必要将应用语言转换（默认值）。false - 不会应用语言转换。 |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | 获取编辑文本的裁剪路径处理模式。 |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | 获取定义字体替换场景行为的模式。 |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | 获取定义语言转换场景行为的模式。 |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | 获取或设置在字体不包含所需字符时定义行为的模式。 |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | 获取或设置在用户字体不包含所需字符时用于替换的字体。 |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | 获取或设置是否允许在源文档页面上搜索文本下划线的值。（已弃用）请改用 TextSearchOptions.SearchForTextRelatedGraphics。 |

### 另请参见

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


