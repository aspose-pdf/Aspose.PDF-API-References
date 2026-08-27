---
title: "PdfExtractor.StartPage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti PdfExtractor. Mendapatkan atau mengatur halaman mulai dalam rentang halaman tempat operasi ekstraksi akan dilakukan"
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage property

Mendapatkan atau mengatur halaman mulai dalam rentang halaman tempat operasi ekstraksi akan dilakukan.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


