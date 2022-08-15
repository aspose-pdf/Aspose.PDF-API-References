---
title: SaveAsTIFF
second_title: Aspose.PDF for .NET API Referansı
description: Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya. |

### Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Çıktı dosyası. |
| compressionType | CompressionType | Sıkıştırma türü. |

### Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### Ayrıca bakınız

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya adı |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Bir pdf belgesinin her sayfasını sayfa boyutuna sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya adı |
| pageSize | PageSize | Resmin sayfa boyutu. |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Bir pdf belgesinin her sayfasını sayfa boyutuna sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya adı |
| pageSize | PageSize | Resmin sayfa boyutu. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya adı |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |
| compressionType | CompressionType | Sıkıştırma türü. |

### Ayrıca bakınız

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya adı |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |

### Ayrıca bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Bir pdf belgesinin her sayfasını boyutlu görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya adı |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |
| converter | IIndexBitmapConverter | Harici dönüştürücü |

### Ayrıca bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Çıkış akışı. |
| compressionType | CompressionType | Sıkıştırma türü. |

### Ayrıca bakınız

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Bir pdf belgesinin her sayfasını sayfa boyutuna sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| pageSize | PageSize | Resmin sayfa boyutu. |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Bir pdf belgesinin her sayfasını sayfa boyutuna sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Bir pdf belgesinin her sayfasını boyutlara sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Bir pdf belgesinin her sayfasını boyutlara sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |
| compressionType | CompressionType | Sıkıştırma türü. |

### Ayrıca bakınız

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Bir pdf belgesinin her sayfasını boyutlara sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |

### Ayrıca bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Bir pdf belgesinin her sayfasını boyutlara sahip görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |
| converter | IIndexBitmapConverter | Harici dönüştürücü |

### Ayrıca bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya adı |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |

### Ayrıca bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünün kaydedileceği dosya adı |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |
| converter | IIndexBitmapConverter | Harici dönüştürücü |

### Ayrıca bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |

### Ayrıca bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayarlar nesnesi. |
| converter | IIndexBitmapConverter | Harici dönüştürücü |

### Ayrıca bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
