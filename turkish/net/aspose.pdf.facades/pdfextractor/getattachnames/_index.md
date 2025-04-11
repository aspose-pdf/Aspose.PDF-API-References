---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor metodu. PDF dosyasındaki eklerin listesini döndürür. Not: Bu metodu kullanmadan önce ExtractAttachments çağrılmalıdır.
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames metodu

PDF dosyasındaki eklerin listesini döndürür. Not: Bu metodu kullanmadan önce ExtractAttachments çağrılmalıdır.

```csharp
public IList<string> GetAttachNames()
```

### Dönüş Değeri

Eklerin listesi

## Örnekler

Örnek, PDF dosyasından ek isimlerini çıkarmanın nasıl yapılacağını gösterir.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)