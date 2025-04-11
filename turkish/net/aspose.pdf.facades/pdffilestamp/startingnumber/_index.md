---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp özelliği. Giriş dosyasındaki ilk sayfa için başlangıç numarasını alır veya ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılacaktır. Örneğin, BaşlangıçNumarası 100 olarak ayarlandığında, belge sayfaları 100, 101, 102 numaralarına sahip olacaktır.
type: docs
weight: 100
url: /tr/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## PdfFileStamp.BaşlangıçNumarası özelliği

Giriş dosyasındaki ilk sayfa için başlangıç numarasını alır veya ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılacaktır. Örneğin, BaşlangıçNumarası 100 olarak ayarlandığında, belge sayfaları 100, 101, 102... numaralarına sahip olacaktır.

```csharp
public int StartingNumber { get; set; }
```

## Örnekler

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Ayrıca Bakınız

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)