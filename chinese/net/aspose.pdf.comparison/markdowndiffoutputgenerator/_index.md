---
title: "类 MarkdownDiffOutputGenerator"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator 类。表示用于生成文本差异的 markdown 表示的类。由于 markdown 语法，无法显示对空白字符的更改。选择更改会在格式周围添加空白字符，否则 markdown 查看器将无法正确显示文本。已删除的换行符以段落标记表示"
type: docs
weight: 3360
url: /zh/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class

表示用于生成文本差异的 Markdown 表示的类。由于 Markdown 语法，无法显示空白字符的更改。对更改的选择会在格式周围添加空白字符，否则 Markdown 查看器将无法正确显示文本。已删除的换行以 - 段落标记表示。

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | 根据文本之间的差异生成输出并将其保存到文件中。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | 根据文本之间的差异生成输出并将其保存到文件中。 |

### 另请参见

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


