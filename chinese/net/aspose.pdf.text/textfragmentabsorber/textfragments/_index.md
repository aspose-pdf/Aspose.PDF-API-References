---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 属性。获取以 TextFragment 对象呈现的搜索出现的集合
type: docs
weight: 90
url: /zh/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments 属性

获取以 [`TextFragment`](../../textfragment/) 对象呈现的搜索出现的集合。

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## 示例

该示例演示如何在第一个 PDF 文档页面上查找文本并用新文本替换所有搜索出现的内容。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* 类 [TextFragmentCollection](../../textfragmentcollection/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)