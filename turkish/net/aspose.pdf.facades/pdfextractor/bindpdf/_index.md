---
title: PdfExtractor.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor metodu. Girdi PDF dosyasını bağla
type: docs
weight: 100
url: /tr/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Girdi PDF dosyasını bağlar.

```csharp
public override void BindPdf(string inputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Bağlanacak PDF dosyası |

## Örnekler

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Akıştan PDF belgesini bağlar.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | PDF belgesi verilerini içeren akış |

## Örnekler

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)