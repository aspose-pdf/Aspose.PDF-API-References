---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor özelliği. Çıkarma işleminin gerçekleştirileceği sayfa aralığında başlangıç sayfasını alır veya ayarlar
type: docs
weight: 80
url: /tr/net/aspose.pdf.facades/pdfextractor/startpage/
---
## PdfExtractor.StartPage özelliği

Çıkarma işleminin gerçekleştirileceği sayfa aralığında başlangıç sayfasını alır veya ayarlar.

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

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)