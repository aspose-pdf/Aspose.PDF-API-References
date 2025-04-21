---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor metodu. PDF belgesinden bir sonraki resmi alır. Not Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır.
type: docs
weight: 170
url: /tr/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

PDF belgesinden bir sonraki resmi alır. Not: Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır.

```csharp
public bool GetNextImage(string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmin saklanacağı dosya |

### Dönüş Değeri

Resim başarıyla çıkarıldığında True döner.

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

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Verilen resim formatıyla PDF belgesinden bir sonraki resmi alır. Not: Bu yöntemi kullanmadan önce ExtractImage çağrılmalıdır.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmin saklanacağı dosya |
| format | ImageFormat | Resmin formatı. |

### Dönüş Değeri

Resim başarıyla çıkarıldığında True döner.

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

PDF dosyasından bir sonraki resmi alır ve belirtilen resim formatıyla akışa kaydeder.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resim verilerinin kaydedileceği akış |
| format | ImageFormat | Resmin formatı. |

### Dönüş Değeri

Resim başarıyla çıkarıldığında True döner.

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

PDF dosyasından bir sonraki resmi alır ve akışa kaydeder.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resim verilerinin kaydedileceği akış |

### Dönüş Değeri

Resim başarıyla çıkarıldığında True döner.

### Ayrıca Bakınız

* sınıf [PdfExtractor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)