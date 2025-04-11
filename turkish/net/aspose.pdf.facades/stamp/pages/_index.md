---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Damga özelliği. Damgadan etkilenecek sayfa numaralarının bulunduğu diziyi alır veya ayarlar. Eğer Sayfalar null ise, belgenin tüm sayfaları etkilenir.
type: docs
weight: 60
url: /tr/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages özelliği

Damgadan etkilenecek sayfa numaralarının bulunduğu diziyi alır veya ayarlar. Eğer Sayfalar = null ise, belgenin tüm sayfaları etkilenir.

```csharp
public int[] Pages { get; set; }
```

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [Stamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)