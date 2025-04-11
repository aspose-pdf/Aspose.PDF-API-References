---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 属性。获取或设置 TextFragmentAbsorber 在 PDF 文档或页面上搜索的短语
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase 属性

获取或设置短语，该短语由 [`TextFragmentAbsorber`](../) 在 PDF 文档或页面上搜索。

```csharp
public string Phrase { get; set; }
```

## 示例

该示例演示如何多次执行文本搜索并进行文本替换。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)