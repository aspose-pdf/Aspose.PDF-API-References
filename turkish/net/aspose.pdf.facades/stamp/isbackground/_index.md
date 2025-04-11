---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Stamp özelliği. Arka plan durumunu alır veya ayarlar. Eğer doğruysa, damga, damgalanmış sayfanın arka planı olarak yerleştirilecektir. Varsayılan olarak false olarak ayarlanmıştır.
type: docs
weight: 30
url: /tr/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground özelliği

Arka plan durumunu alır veya ayarlar. Eğer doğruysa, damga, damgalanmış sayfanın arka planı olarak yerleştirilecektir. Varsayılan olarak false olarak ayarlanmıştır.

```csharp
public bool IsBackground { get; set; }
```

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [Stamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)