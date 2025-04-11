---
title: PdfConverter.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter-metod. Sparar bild till fil med standard bildformat - jpeg
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Sparar bild till fil med standard bildformat - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Sparar bild till fil med angiven sidstorlek och standard bildformat - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Sparar bild till fil med det angivna bildformatet.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |

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

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Sparar bild till fil med angiven sidstorlek och bildformat.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |
| format | ImageFormat | Formatet för bilden. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Sparar bild till ström med standard bildformat - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Sparar bild till ström med angiven sidstorlek.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Sparar bild till ström med angivet bildformat.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Sparar bild till ström med angiven sidstorlek.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |
| format | ImageFormat | Formatet för bilden. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Sparar bild till fil med det angivna bildformatet, dimensionerna och kvaliteten.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| quality | Int32 | Kvaliteten på Jpeg-filen (0~100), 0 är lägst och 100 är högst |

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

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Sparar bild till ström med det angivna bildformatet, dimensionerna och kvaliteten.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| quality | Int32 | Kvaliteten på Jpeg-filen (0~100), 0 är lägst och 100 är högst |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Sparar bild till fil med det angivna bildformatet, bildstorleken och kvaliteten.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |
| imageWidth | Double | Bildens bredd, enheten är pixlar. |
| imageHeight | Double | Bildens höjd, enheten är pixlar. |
| quality | Int32 | Kvaliteten på Jpeg-filen (0~100), 0 är lägst och 100 är högst |

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

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Sparar bild till ström med det angivna bildformatet, storleken och kvaliteten.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |
| imageWidth | Double | Bildens bredd, enheten är pixel. |
| imageHeight | Double | Bildens höjd, enheten är pixel. |
| quality | Int32 | Kvaliteten på Jpeg-filen (0~100), 0 är lägst och 100 är högst |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Sparar bild till fil med det angivna bildformatet och dimensionerna.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |
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

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Sparar bild till ström med det angivna bildformatet, storleken och kvaliteten.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Sparar bild till ström med angivet bildformat och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |
| quality | Int32 | Kvaliteten på Jpeg-filen (0~100), 0 är lägst och 100 är högst |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Sparar bild till ström med angiven sidstorlek, bildformat och kvalitet.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |
| format | ImageFormat | Formatet för bilden. |
| quality | Int32 | Kvaliteten på Jpeg-filen (0~100), 0 är lägst och 100 är högst |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Sparar bild till fil med angivet bildformat och kvalitet.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |
| format | ImageFormat | Formatet för bilden. |
| quality | Int32 | Kvaliteten på Jpeg-filen (0~100), 0 är lägst och 100 är högst |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Sparar bild till fil med angiven sidstorlek, bildformat och kvalitet.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filvägen och namnet för att spara bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |
| format | ImageFormat | Formatet för bilden. |
| quality | Int32 | Kvaliteten på Jpeg-filen (0~100), 0 är lägst och 100 är högst |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)