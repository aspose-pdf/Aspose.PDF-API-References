---
title: PdfConverter.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter metodu. Varsayılan resim formatı jpeg ile resmi dosyaya kaydeder
type: docs
weight: 140
url: /tr/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Varsayılan resim formatı - jpeg ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Verilen sayfa boyutu ve varsayılan resim formatı - jpeg ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |
| pageSize | PageSize | Resmin sayfa boyutu. |

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Verilen resim formatı ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Verilen sayfa boyutu ve resim formatı ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| format | ImageFormat | Resmin formatı. |

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Varsayılan resim formatı - jpeg ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Verilen sayfa boyutu ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |
| pageSize | PageSize | Resmin sayfa boyutu. |

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Verilen resim formatı ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Verilen sayfa boyutu ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| format | ImageFormat | Resmin formatı. |

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Verilen resim formatı, boyutları ve kalitesi ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Int32 | Resmin genişliği, birim piksel. |
| imageHeight | Int32 | Resmin yüksekliği, birim piksel. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Verilen resim formatı, boyutları ve kalitesi ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Int32 | Resmin genişliği, birim piksel. |
| imageHeight | Int32 | Resmin yüksekliği, birim piksel. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Verilen resim formatı, resim boyutu ve kalitesi ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Double | Resmin genişliği, birim piksel. |
| imageHeight | Double | Resmin yüksekliği, birim piksel. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Verilen resim formatı, boyutu ve kalitesi ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Double | Resmin genişliği, birim piksel. |
| imageHeight | Double | Resmin yüksekliği, birim piksel. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Verilen resim formatı ve boyutları ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Int32 | Resmin genişliği, birim piksel. |
| imageHeight | Int32 | Resmin yüksekliği, birim piksel. |

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Verilen resim formatı, boyutu ve kalitesi ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |
| imageWidth | Int32 | Resmin genişliği, birim piksel. |
| imageHeight | Int32 | Resmin yüksekliği, birim piksel. |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Verilen resim formatı ve kalitesi ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |
| format | ImageFormat | Resmin formatı. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Verilen sayfa boyutu, resim formatı ve kalitesi ile resmi akışa kaydeder.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputStream | Stream | Resmi kaydetmek için akış. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| format | ImageFormat | Resmin formatı. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Verilen resim formatı ve kalitesi ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |
| format | ImageFormat | Resmin formatı. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca Bakınız

* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Verilen sayfa boyutu, resim formatı ve kalitesi ile resmi dosyaya kaydeder.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFile | String | Resmi kaydetmek için dosya yolu ve adı. |
| pageSize | PageSize | Resmin sayfa boyutu. |
| format | ImageFormat | Resmin formatı. |
| quality | Int32 | Jpeg dosyasının kalitesi (0~100), 0 en düşük ve 100 en yüksek |

### Ayrıca Bakınız

* sınıf [PageSize](../../../aspose.pdf/pagesize/)
* sınıf [PdfConverter](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)