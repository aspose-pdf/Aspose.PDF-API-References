---
title: "枚举 TextEditOptions.NoCharacterAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextEditOptionsNoCharacterAction 枚举。若字体不包含所需字符时要执行的操作"
type: docs
weight: 11040
url: /zh/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

当字体不包含所需字符时执行的操作

```csharp
public enum NoCharacterAction
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ThrowException | `0` | 抛出异常 |
| UseStandardFont | `1` | 将字体替换为包含所需字符的标准字体 |
| ReplaceAnyway | `2` | 仍然替换文本而不进行字体替换 |
| ReplaceFonts | `3` | 根据需要替换字体，以确保文本中的所有字符均可显示。字体替换算法遵循以下步骤：1. 如果用户显式设置了 Font 属性，检查指定的字体是否能够显示所需字符。2. 如果未设置用户自定义字体，则搜索通过 [`Sources`](../fontrepository/sources/) 添加的字体。3. 分析文本以识别其字母表或书写系统，并相应地建议字体名称。尝试在系统中定位并使用这些字体。4. 作为后备，搜索系统中任何能够显示所需字符的字体。 |
| UseCustomReplacementFont | `4` | 将字体替换为定义的替代字体 |

### 另请参见

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


