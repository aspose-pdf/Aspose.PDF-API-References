---
title: "RenderingOptions.AnalyzeFonts"
second_title: "Aspose.PDF for .NET API 参考"
description: "RenderingOptions 属性。根据需要替换字体，以确保文本中的所有字符都能显示。字体替换算法遵循以下步骤：1. 如果用户显式设置了 DefaultFontName 属性，检查指定的字体是否能够显示所需字符。2. 如果未设置用户自定义字体，则搜索通过 FontRepository.Sources 添加的字体。3. 分析文本以识别其字母表或书写系统，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备，搜索系统中任何能够显示所需字符的字体。"
type: docs
weight: 20
url: /zh/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts property

根据需要替换字体，以确保文本中的所有字符都能显示。字体替换算法遵循以下步骤：1. 如果用户显式设置了 DefaultFontName 属性，检查指定的字体是否能够显示所需字符。2. 如果未设置用户自定义字体，则搜索通过 !:FontRepository.Sources 添加的字体。3. 分析文本以识别其字母表或文字脚本，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备方案，搜索系统中任何能够显示所需字符的字体。

```csharp
public bool AnalyzeFonts { get; set; }
```

### 另请参见

* class [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


