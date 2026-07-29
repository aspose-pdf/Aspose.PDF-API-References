---
title: "TextFragmentAbsorber.RegexResults"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragmentAbsorber 属性。获取搜索出现次数的字典，该字典以 System.Text.RegularExpressions.Regex 类为键，TextFragment 为值"
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults property

获取搜索出现次数的字典，该字典以 System.Text.RegularExpressions.Regex 类为键，[`TextFragment`](../../textfragment/) 为值。

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## 示例

示例演示了如何在第一页 PDF 文档上使用正则表达式数组查找文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// 创建 TextFragmentAbsorber 对象，使用正则表达式搜索所有以 'h' 开头并以 'o' 结尾的单词。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// 获取结果
var results = absorber.RegexResults;
```

### 另请参见

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


