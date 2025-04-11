---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Font özelliği. Fontun sistemde yüklü olup olmadığını gösterir.
type: docs
weight: 50
url: /tr/net/aspose.pdf.text/font/isaccessible/
---
## Font.Erişilebilir özelliği

Fontun sistemde mevcut (yüklü) olup olmadığını gösterir.

```csharp
public bool IsAccessible { get; }
```

## Açıklamalar

Sistemde bulunamayan fontlarla bazı işlemler yapılamaz.

## Örnekler

Örnek, ilk sayfadaki metni nasıl arayacağınızı ve fontun sistemde yüklü olup olmadığını gösteren değeri nasıl alacağınızı gösterir.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Ayrıca Bakınız

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)