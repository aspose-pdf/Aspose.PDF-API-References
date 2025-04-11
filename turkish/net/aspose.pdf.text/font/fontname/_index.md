---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Font özelliği. Font nesnesinin font adını alır
type: docs
weight: 30
url: /tr/net/aspose.pdf.text/font/fontname/
---
## Font.FontName özelliği

[`Font`](../) nesnesinin font adını alır.

```csharp
public string FontName { get; }
```

## Örnekler

Örnek, ilk sayfadaki metni nasıl arayacağınızı ve ilk metin oluşumunun font adını nasıl görüntüleyeceğinizi gösterir.

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

### Ayrıca Bakınız

* sınıf [TextFragmentAbsorber](../../textfragmentabsorber/)
* sınıf [Document](../../../aspose.pdf/document/)
* sınıf [Font](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)