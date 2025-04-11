---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 属性。获取或设置表示 TextFragment 对象的字符串文本对象
type: docs
weight: 130
url: /zh/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text 属性

获取或设置表示 [`TextFragment`](../) 对象的字符串文本对象。

```csharp
public string Text { get; set; }
```

## 示例

该示例演示如何搜索文本并替换由 [`TextFragment`](../) 对象表示的第一个出现。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参阅

* 类 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 类 [Document](../../../aspose.pdf/document/)
* 类 [TextFragment](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)