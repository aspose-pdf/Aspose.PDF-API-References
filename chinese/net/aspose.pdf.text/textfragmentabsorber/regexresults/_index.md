---
title: TextFragmentAbsorber.RegexResults
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 属性。获取以 System.Text.RegularExpressions.Regex 类作为键，以 TextFragment 作为值的搜索出现字典
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/textfragmentabsorber/regexresults/
---
## TextFragmentAbsorber.RegexResults 属性

获取以 System.Text.RegularExpressions.Regex 类作为键，以 [`TextFragment`](../../textfragment/) 作为值的搜索出现字典。

```csharp
public Dictionary<Regex, TextFragmentCollection> RegexResults { get; }
```

## 示例

该示例演示如何在第一个 PDF 文档页面上使用正则表达式数组查找文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results
var results = absorber.RegexResults;
```

### 另请参阅

* 类 [TextFragmentCollection](../../textfragmentcollection/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)