---
title: "类 HtmlDiffOutputGenerator"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator 类。表示用于生成文本差异的 html 表示的类。已删除的换行符以段落标记表示。"
type: docs
weight: 3310
url: /zh/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

表示用于生成文本差异的 HTML 表示的类。已删除的换行以段落标记表示。

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | 创建 `HtmlDiffOutputGenerator` 类的实例。 |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | 创建 `HtmlDiffOutputGenerator` 类的实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | 获取和设置用于 Delete 操作的 CSS 样式字符串。示例： |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | 获取和设置用于 Equal 操作的 CSS 样式字符串。示例： |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | 获取和设置用于 Insert 操作的 CSS 样式字符串。示例： |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | 获取或设置删除操作的 text-decoration: line-through 样式。默认值为 `False`。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | 根据文本之间的差异生成输出并将其保存到文件中。 |

### 另请参见

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


