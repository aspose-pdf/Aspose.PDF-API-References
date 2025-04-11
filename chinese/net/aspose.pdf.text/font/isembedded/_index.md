---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: 字体属性。获取或设置一个值，该值指示字体是否嵌入。基于 IFont 的字体将自动进行子集化并嵌入
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded 属性

获取或设置一个值，该值指示字体是否嵌入。基于 IFont 的字体将自动进行子集化并嵌入

```csharp
public bool IsEmbedded { get; set; }
```

## 示例

以下示例演示如何查找字体，将其标记为嵌入，搜索文档页面上的文本并替换文本字体。

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参阅

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)