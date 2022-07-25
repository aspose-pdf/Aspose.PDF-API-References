---
title: GetNextImage
second_title: Aspose.PDF för .NET API Referens
description: Sparar bild till fil med standardbildformat - jpeg.
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Sparar bild till fil med standardbildformat - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Sparar bild till fil med given sidstorlek och standardbildformat - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Sparar bild till fil med givin bildformat.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |
| format | ImageFormat | Bildens format. |

### Exempel

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

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Sparar bild till fil med given sidstorlek och bildformat.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| format | ImageFormat | Bildens format. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Sparar bild för att streama med standardbildformat - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Sparar bild för att streama med given sidstorlek.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Sparar bild för att streama med givet bildformat.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |
| format | ImageFormat | Bildens format. |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Sparar bild för att streama med given sidstorlek.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| format | ImageFormat | Bildens format. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Sparar bild till fil med angivet bildformat, mått och kvalitet.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |
| quality | Int32 | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Exempel

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

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Sparar bild för att streama med givin bildformat, mått och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |
| quality | Int32 | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Sparar bild till fil med givin bildformat, bildstorlek och kvalitet.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Double | Bildens bredd, enheten är pixlar. |
| imageHeight | Double | Bildhöjden, enheten är pixlar.. |
| quality | Int32 | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Exempel

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

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Sparar bild för att streama med givin bildformat, storlek och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Double | Bildens bredd, enheten är pixel. |
| imageHeight | Double | Bildhöjden, enheten är pixel. |
| quality | Int32 | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Sparar bild till fil med angivet bildformat och mått.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |

### Exempel

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

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Sparar bild för att streama med givin bildformat, storlek och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |
| format | ImageFormat | Bildens format. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Sparar bild för att streama med givet bildformat och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |
| format | ImageFormat | Bildens format. |
| quality | Int32 | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Sparar bild för att streama med given sidstorlek, bildformat och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| format | ImageFormat | Bildens format. |
| quality | Int32 | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Sparar bild till fil med givet bildformat och kvalitet.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |
| format | ImageFormat | Bildens format. |
| quality | Int32 | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Sparar bild till fil med given sidstorlek, bildformat och kvalitet.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filsökvägen och namnet för att spara bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| format | ImageFormat | Bildens format. |
| quality | Int32 | Jpeg-filens kvalitet (0~100), 0 är lägst och 100 är högst |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
