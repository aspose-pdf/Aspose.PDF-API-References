---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Font özelliği. Fontun bir alt küme olup olmadığını belirten bir değeri alır veya ayarlar. IFont'a dayalı font otomatik olarak alt küme ve gömülü olacaktır.
type: docs
weight: 70
url: /tr/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset özelliği

Fontun bir alt küme olup olmadığını belirten bir değeri alır veya ayarlar. IFont'a dayalı font otomatik olarak alt küme ve gömülü olacaktır.

```csharp
public bool IsSubset { get; set; }
```

## Örnekler

Örnek, ilk sayfadaki metni nasıl arayacağınızı ve fontun bir alt küme olup olmadığını belirten değeri nasıl alacağınızı gösterir.

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

### Ayrıca Bakınız

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)