---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction 枚举。如果字体不包含所需字符，则执行的操作
type: docs
weight: 10860
url: /zh/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction 枚举

如果字体不包含所需字符，则执行的操作

```csharp
public enum NoCharacterAction
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ThrowException | `0` | 抛出异常 |
| UseStandardFont | `1` | 替换为包含所需字符的标准字体 |
| ReplaceAnyway | `2` | 无论如何替换文本而不进行字体替换 |
| ReplaceFonts | `3` | 根据需要替换字体，以确保文本中的所有字符都可以显示。字体替换算法遵循以下步骤：1. 如果用户明确设置了 Font 属性，检查指定的字体是否可以显示所需的字符。2. 如果未设置用户定义的字体，则通过 [`Sources`](../fontrepository/sources/) 中添加的字体进行搜索。3. 分析文本以识别其字母表或脚本，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备，搜索系统中任何能够显示所需字符的字体。 |
| UseCustomReplacementFont | `4` | 替换为定义的替换字体 |

### 另请参见

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)