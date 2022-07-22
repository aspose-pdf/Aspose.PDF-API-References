---
title: GetNextImage
second_title: Aspose.PDF for .NET API Referansı
description: Görüntüyü varsayılan görüntü biçimiyle dosyaya kaydeder - jpeg.
type: docs
weight: 140
url: /tr/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Görüntüyü varsayılan görüntü biçimiyle dosyaya kaydeder - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Görüntüyü belirtilen sayfa boyutu ve varsayılan görüntü biçimiyle dosyaya kaydeder - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |
| pageSize | PageSize | Resmin sayfa boyutu. |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Görüntüyü verilen görüntü biçimiyle dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |

### Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".png";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".png" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png)
	imageCount = imageCount + 1
End While
```

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Görüntüyü belirtilen sayfa boyutu ve görüntü biçimiyle dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| format | ImageFormat | Resmin formatı. |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Görüntüyü varsayılan görüntü biçimiyle akışa kaydeder - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Görüntüyü verilen sayfa boyutuyla akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |
| pageSize | PageSize | Resmin sayfa boyutu. |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Görüntüyü, verilen görüntü biçimiyle akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Görüntüyü verilen sayfa boyutuyla akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| format | ImageFormat | Resmin formatı. |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Görüntüyü verilen görüntü formatı, boyutları ve kalitesiyle dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50)
	imageCount = imageCount + 1
End While
```

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Verilen görüntü formatı, boyutları ve kalitesi ile görüntüyü akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Görüntüyü, verilen görüntü formatı, görüntü boyutu ve kalitesiyle dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Double | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Double | Görüntü yüksekliği, birimi pikseldir.. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
float pixelX=800f;
float pixelY=600f;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim pixelX As float =800
Dim pixelY As float=600
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50)
	imageCount = imageCount + 1
End While
```

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Görüntü formatı, boyutu ve kalitesi ile akış için görüntüyü kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Double | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Double | Görüntü yüksekliği, birim pikseldir. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Görüntüyü verilen görüntü formatı ve boyutlarıyla dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |

### Örnekler

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000)
	imageCount = imageCount + 1
End While
```

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Görüntü formatı, boyutu ve kalitesi ile akış için görüntüyü kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Int32 | Görüntü genişliği, birimi pikseldir. |
| imageHeight | Int32 | Görüntü yüksekliği, birim pikseldir. |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Görüntüyü, verilen görüntü formatı ve kalitesiyle akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Görüntüyü belirtilen sayfa boyutu, görüntü formatı ve kalitesiyle akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputStream | Stream | Görüntüyü kaydetmek için akış. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| format | ImageFormat | Resmin formatı. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Görüntüyü, verilen görüntü formatı ve kalitesiyle dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca bakınız

* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Görüntüyü belirtilen sayfa boyutu, görüntü formatı ve kalitesiyle dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFile | String | Resmin kaydedileceği dosya yolu ve adı. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| format | ImageFormat | Resmin formatı. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca bakınız

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* ad alanı [Aspose.Pdf.Facades](../../pdfconverter)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
