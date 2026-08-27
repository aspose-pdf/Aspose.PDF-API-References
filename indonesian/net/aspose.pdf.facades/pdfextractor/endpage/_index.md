---
title: "PdfExtractor.EndPage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti PdfExtractor. Mendapatkan atau mengatur halaman akhir dalam rentang halaman tempat operasi ekstraksi akan dilakukan."
type: docs
weight: 20
url: /id/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

Mendapatkan atau mengatur halaman akhir dalam rentang halaman tempat operasi ekstraksi akan dilakukan.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


