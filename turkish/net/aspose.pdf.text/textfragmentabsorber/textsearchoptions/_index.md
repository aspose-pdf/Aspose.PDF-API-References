---
title: TextSearchOptions
second_title: Aspose.PDF for .NET API Referansı
description: Arama seçeneklerini alır veya ayarlar. Seçenekler normal ifadeler kullanarak aramayı etkinleştirir.
type: docs
weight: 100
url: /tr/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

Arama seçeneklerini alır veya ayarlar. Seçenekler, normal ifadeler kullanarak aramayı etkinleştirir.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

### Örnekler

Örnek, normal ifade kullanarak arama metninin nasıl gerçekleştirileceğini gösterir.

```csharp
// Belgeyi aç
Document doc = new Document(@"D:\Tests\input.pdf");

// TextFragmentAbsorber nesnesi oluştur
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// emicinin normal ifadeyi kullanarak 'h' ile başlayan ve 'o' ile biten tüm kelimeleri aramasını sağlayın.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// "merhaba" kelimesini bulmalı ve "Merhaba" ile değiştirmeliyiz
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Belgeyi kaydet
doc.Save(@"D:\Tests\output.pdf"); 
```

### Ayrıca bakınız

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* ad alanı [Aspose.Pdf.Text](../../textfragmentabsorber)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->