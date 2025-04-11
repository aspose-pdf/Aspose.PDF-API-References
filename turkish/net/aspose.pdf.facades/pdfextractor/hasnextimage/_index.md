---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor metodu. PDF belgesinde daha fazla görüntünün erişilebilir olup olmadığını kontrol eder. Not: Bu metodun kullanımı öncesinde ExtractImage çağrılmalıdır.
type: docs
weight: 200
url: /tr/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage metodu

PDF belgesinde daha fazla görüntünün erişilebilir olup olmadığını kontrol eder. Not: Bu metodun kullanımı öncesinde ExtractImage çağrılmalıdır.

```csharp
public bool HasNextImage()
```

### Dönüş Değeri

Daha fazla görüntü erişilebilir ise doğru döner.

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)