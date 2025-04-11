---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: 字体属性。获取 Font 对象的字体名称
type: docs
weight: 30
url: /zh/net/aspose.pdf.text/font/fontname/
---
## Font.FontName 属性

获取 [`Font`](../) 对象的字体名称。

```csharp
public string FontName { get; }
```

## 示例

该示例演示如何在第一页上搜索文本并查看第一个文本出现的字体名称。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### 另请参阅

* 类 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 类 [Document](../../../aspose.pdf/document/)
* 类 [Font](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)