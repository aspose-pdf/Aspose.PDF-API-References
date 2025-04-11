---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp metodu. Dosyaya damga ekler
type: docs
weight: 140
url: /tr/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp metodu

Dosyaya damga ekler.

```csharp
public void AddStamp(Stamp stamp)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| damga | Stamp | Damga nesnesi. |

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ayrıca Bakınız

* sınıf [Stamp](../../stamp/)
* sınıf [PdfFileStamp](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)