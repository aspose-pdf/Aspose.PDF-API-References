---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 属性。获取或设置搜索选项。选项允许使用正则表达式进行搜索
type: docs
weight: 110
url: /zh/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions 属性

获取或设置搜索选项。选项允许使用正则表达式进行搜索。

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## 示例

该示例演示如何使用正则表达式执行文本搜索。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参阅

* 类 [TextSearchOptions](../../textsearchoptions/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)