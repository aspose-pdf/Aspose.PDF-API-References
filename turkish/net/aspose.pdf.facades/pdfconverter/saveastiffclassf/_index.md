---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter metodu. Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder
type: docs
weight: 170
url: /tr/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |

## Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için akış. |
| pageSize | PageSize | Görüntünün sayfa boyutu. |

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| pageSize | PageSize | Görüntünün sayfa boyutu. |

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF dosyasına kaydeder.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için akış. |

## Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF ClassF akışına kaydeder.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)