---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: Properti PdfExtractor. Mendapatkan atau mengatur halaman awal dalam rentang halaman di mana operasi ekstraksi akan dilakukan
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/pdfextractor/startpage/
---
## Properti PdfExtractor.StartPage

Mendapatkan atau mengatur halaman awal dalam rentang halaman di mana operasi ekstraksi akan dilakukan.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### Lihat Juga

* kelas [PdfExtractor](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)