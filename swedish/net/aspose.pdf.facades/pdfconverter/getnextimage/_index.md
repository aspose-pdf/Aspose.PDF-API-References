---
title: "PdfConverter.GetNextImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfConverter-metoden. Sparar bilden till fil med standardbildformatet jpeg"
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Sparar bilden till en fil med standardbildformatet - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Sparar bilden till en fil med den angivna sidstorleken och standardbildformatet - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Sparar bilden till en fil med det angivna bildformatet.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |
| format | ImageFormat | Bildens format. |

## Exempel

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

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Sparar bilden till en fil med angiven sidstorlek och bildformat.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| format | ImageFormat | Bildens format. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Sparar bilden till en ström med standardbildformatet - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Sparar bilden till en ström med angiven sidstorlek.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Sparar bilden till en ström med angivet bildformat.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |
| format | ImageFormat | Bildens format. |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Sparar bilden till en ström med angiven sidstorlek.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| format | ImageFormat | Bildens format. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Sparar bilden till en fil med det angivna bildformatet, dimensionerna och kvaliteten.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| kvalitet | Int32 | JPEG-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Exempel

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

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Sparar bilden till en ström med det angivna bildformatet, dimensionerna och kvaliteten.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| kvalitet | Int32 | JPEG-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Sparar bilden till en fil med det angivna bildformatet, bildstorleken och kvaliteten.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Double | Bildens bredd, enheten är pixlar. |
| imageHeight | Double | Bildens höjd, enheten är pixlar.. |
| kvalitet | Int32 | JPEG-filens kvalitet (0~100), 0 är lägst och 100 är högst |

## Exempel

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

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Sparar bilden till en ström med det angivna bildformatet, storleken och kvaliteten.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Double | Bildens bredd, enheten är pixel. |
| imageHeight | Double | Bildens höjd, enheten är pixel. |
| kvalitet | Int32 | JPEG-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Sparar bilden till en fil med det angivna bildformatet och dimensionerna.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |

## Exempel

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

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Sparar bilden till en ström med det angivna bildformatet, storleken och kvaliteten.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Sparar bilden till en ström med angivet bildformat och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |
| format | ImageFormat | Bildens format. |
| kvalitet | Int32 | JPEG-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Sparar bilden till en ström med angiven sidstorlek, bildformat och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Strömmen för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| format | ImageFormat | Bildens format. |
| kvalitet | Int32 | JPEG-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Sparar bilden till en fil med angivet bildformat och kvalitet.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |
| format | ImageFormat | Bildens format. |
| kvalitet | Int32 | JPEG-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Sparar bilden till en fil med angiven sidstorlek, bildformat och kvalitet.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filens sökväg och namn för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| format | ImageFormat | Bildens format. |
| kvalitet | Int32 | JPEG-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


