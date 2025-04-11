---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor özelliği. Çıkarma işleminin gerçekleştirileceği sayfa aralığında son sayfayı alır veya ayarlar
type: docs
weight: 20
url: /tr/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage özelliği

Çıkarma işleminin gerçekleştirileceği sayfa aralığında son sayfayı alır veya ayarlar.

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

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)