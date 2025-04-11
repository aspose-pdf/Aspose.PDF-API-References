---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: 字体属性。获取或设置一个值，该值指示字体是否为子集。基于 IFont 的字体将自动成为子集并嵌入
type: docs
weight: 70
url: /zh/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset 属性

获取或设置一个值，该值指示字体是否为子集。基于 IFont 的字体将自动成为子集并嵌入

```csharp
public bool IsSubset { get; set; }
```

## 示例

该示例演示如何在第一页上搜索文本并获取指示字体是否为子集的值。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### 另请参阅

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)