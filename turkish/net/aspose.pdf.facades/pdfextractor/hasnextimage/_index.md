---
title: HasNextImage
second_title: Aspose.PDF for .NET API Referansı
description: PDF belgesinde daha fazla görüntünün erişilebilir olup olmadığını kontrol eder. Not Bu yöntem kullanılmadan önce ExtractImage çağrılmalıdır.
type: docs
weight: 200
url: /tr/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

PDF belgesinde daha fazla görüntünün erişilebilir olup olmadığını kontrol eder. Not: Bu yöntem kullanılmadan önce ExtractImage çağrılmalıdır.

```csharp
public bool HasNextImage()
```

### Geri dönüş değeri

Daha fazla görüntüye erişilebiliyorsa doğrular

### Örnekler

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Ayrıca bakınız

* class [PdfExtractor](../../pdfextractor)
* ad alanı [Aspose.Pdf.Facades](../../pdfextractor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
