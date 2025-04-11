---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.HtmlDiffOutputGenerator class. 表示用于生成文本差异的 HTML 表示的类。删除的换行符由段落标记表示
type: docs
weight: 3200
url: /zh/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

表示用于生成文本差异的 HTML 表示的类。删除的换行符由段落标记表示。

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | 创建 `HtmlDiffOutputGenerator` 类的实例。 |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | 创建 `HtmlDiffOutputGenerator` 类的实例。 |

## Properties

| Name | Description |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | 获取和设置用于删除操作的 CSS 样式字符串。示例： |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | 获取和设置用于相等操作的 CSS 样式字符串。示例： |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | 获取和设置用于插入操作的 CSS 样式字符串。示例： |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | 获取或设置删除操作的文本装饰：删除线样式。默认值为 `False`。 |

## Methods

| Name | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | 根据文本之间的差异生成输出并将其保存到文件。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | 根据文本之间的差异生成输出并将其保存到文件。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | 根据文本之间的差异生成输出并将其保存到文件。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | 根据文本之间的差异生成输出并将其保存到文件。 |

### See Also

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)