---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragmentAbsorber 属性。获取或设置搜索选项。该选项启用使用正则表达式的搜索。"
type: docs
weight: 110
url: /zh/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

获取或设置搜索选项。该选项启用使用正则表达式的搜索。

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## 示例

示例演示如何使用正则表达式执行文本搜索。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// 使吸收器使用正则表达式搜索所有以 'h' 开头并以 'o' 结尾的单词。
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// 我们应该找到 "hello" 单词并将其替换为 "Hi"。
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


