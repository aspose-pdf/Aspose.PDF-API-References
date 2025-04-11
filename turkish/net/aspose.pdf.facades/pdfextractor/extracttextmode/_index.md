---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor özelliği. Metin çıkarma sonuçları için modu ayarlar
type: docs
weight: 40
url: /tr/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode özelliği

Metin çıkarma sonuçları için modu ayarlar.

```csharp
public int ExtractTextMode { get; set; }
```

### Özellik Değeri

0 saf metin modudur ve 1 ham sıralama modudur. Varsayılan 0'dır.

## Örnekler

Örnek, metin çıkarma senaryosunda `ExtractTextMode` özelliğinin kullanımını göstermektedir.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)