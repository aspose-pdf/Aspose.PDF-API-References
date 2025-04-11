---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter metodu. Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder
type: docs
weight: 160
url: /tr/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya. |

## Örnekler

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

### Ayrıca Bakınız

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Çıktı dosyası. |
| compressionType | CompressionType | Sıkıştırma türü. |

## Örnekler

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

### Ayrıca Bakınız

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Bir pdf belgesinin her sayfasını boyutlarıyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya adı |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |

### Ayrıca Bakınız

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Bir pdf belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya adı |
| pageSize | PageSize | Görüntünün sayfa boyutu. |

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Bir pdf belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya adı |
| pageSize | PageSize | Görüntünün sayfa boyutu. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Bir pdf belgesinin her sayfasını boyutlarıyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya adı |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |
| compressionType | CompressionType | Sıkıştırma türü. |

### Ayrıca Bakınız

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Bir pdf belgesinin her sayfasını boyutlarıyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya adı |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |

### Ayrıca Bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Bir pdf belgesinin her sayfasını boyutlarıyla görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya adı |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |
| converter | IIndexBitmapConverter | Harici dönüştürücü |

### Ayrıca Bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |

### Ayrıca Bakınız

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Çıktı akışı. |
| compressionType | CompressionType | Sıkıştırma türü. |

### Ayrıca Bakınız

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Bir pdf belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| pageSize | PageSize | Görüntünün sayfa boyutu. |

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Bir pdf belgesinin her sayfasını sayfa boyutuyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| pageSize | PageSize | Görüntünün sayfa boyutu. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |

### Ayrıca Bakınız

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Bir pdf belgesinin her sayfasını boyutlarıyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |

### Ayrıca Bakınız

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Bir pdf belgesinin her sayfasını boyutlarıyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |
| compressionType | CompressionType | Sıkıştırma türü. |

### Ayrıca Bakınız

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Bir pdf belgesinin her sayfasını boyutlarıyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |

### Ayrıca Bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Bir pdf belgesinin her sayfasını boyutlarıyla görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| imageWidth | Int32 | Görüntü genişliği, birim piksel. |
| imageHeight | Int32 | Görüntü yüksekliği, birim piksel. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |
| converter | IIndexBitmapConverter | Harici dönüştürücü |

### Ayrıca Bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya adı |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |

### Ayrıca Bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF dosyasına kaydeder.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | TIFF görüntüsünü kaydetmek için dosya adı |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |
| converter | IIndexBitmapConverter | Harici dönüştürücü |

### Ayrıca Bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |

### Ayrıca Bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Bir pdf belgesinin her sayfasını görüntülere dönüştürür ve görüntüleri tek bir TIFF akışına kaydeder.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | TIFF görüntüsünü kaydetmek için akış. |
| settings | TiffSettings | TIFF parametrelerini tanımlayan ayar nesnesi. |
| converter | IIndexBitmapConverter | Harici dönüştürücü |

### Ayrıca Bakınız

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)