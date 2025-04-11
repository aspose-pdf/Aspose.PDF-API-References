---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: Properti PdfExtractor. Mendapatkan atau menetapkan halaman akhir dalam rentang halaman di mana operasi ekstraksi akan dilakukan
type: docs
weight: 20
url: /id/net/aspose.pdf.facades/pdfextractor/endpage/
---
## Properti PdfExtractor.EndPage

Mendapatkan atau menetapkan halaman akhir dalam rentang halaman di mana operasi ekstraksi akan dilakukan.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### Lihat Juga

* kelas [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)