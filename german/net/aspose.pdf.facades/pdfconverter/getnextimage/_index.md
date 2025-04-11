---
title: PdfConverter.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter-Methode. Speichert das Bild in einer Datei im Standardbildformat jpeg
type: docs
weight: 140
url: /de/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Speichert das Bild in einer Datei im Standardbildformat - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Standardbildformat - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |
| pageSize | PageSize | Die Seitengröße des Bildes. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Speichert das Bild in einer Datei im angegebenen Bildformat.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |

## Beispiele

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

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Speichert das Bild in einer Datei mit der angegebenen Seitengröße und dem Bildformat.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |
| pageSize | PageSize | Die Seitengröße des Bildes. |
| format | ImageFormat | Das Format des Bildes. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Speichert das Bild im Stream im Standardbildformat - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Speichert das Bild im Stream mit der angegebenen Seitengröße.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |
| pageSize | PageSize | Die Seitengröße des Bildes. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Speichert das Bild im Stream im angegebenen Bildformat.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Speichert das Bild im Stream mit der angegebenen Seitengröße.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |
| pageSize | PageSize | Die Seitengröße des Bildes. |
| format | ImageFormat | Das Format des Bildes. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Speichert das Bild in einer Datei mit dem angegebenen Bildformat, den Abmessungen und der Qualität.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| quality | Int32 | Die Qualität der Jpeg-Datei (0~100), 0 ist am niedrigsten und 100 ist am höchsten |

## Beispiele

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

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Speichert das Bild im Stream im angegebenen Bildformat, den Abmessungen und der Qualität.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| quality | Int32 | Die Qualität der Jpeg-Datei (0~100), 0 ist am niedrigsten und 100 ist am höchsten |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Speichert das Bild in einer Datei mit dem angegebenen Bildformat, der Bildgröße und der Qualität.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |
| imageWidth | Double | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Double | Die Bildhöhe, die Einheit ist Pixel. |
| quality | Int32 | Die Qualität der Jpeg-Datei (0~100), 0 ist am niedrigsten und 100 ist am höchsten |

## Beispiele

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

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Speichert das Bild im Stream im angegebenen Bildformat, der Größe und der Qualität.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |
| imageWidth | Double | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Double | Die Bildhöhe, die Einheit ist Pixel. |
| quality | Int32 | Die Qualität der Jpeg-Datei (0~100), 0 ist am niedrigsten und 100 ist am höchsten |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Speichert das Bild in einer Datei mit dem angegebenen Bildformat und den Abmessungen.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |

## Beispiele

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

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Speichert das Bild im Stream im angegebenen Bildformat, der Größe und der Qualität.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Speichert das Bild im Stream im angegebenen Bildformat und der Qualität.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |
| quality | Int32 | Die Qualität der Jpeg-Datei (0~100), 0 ist am niedrigsten und 100 ist am höchsten |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Speichert das Bild im Stream mit der angegebenen Seitengröße, dem Bildformat und der Qualität.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das Bild zu speichern. |
| pageSize | PageSize | Die Seitengröße des Bildes. |
| format | ImageFormat | Das Format des Bildes. |
| quality | Int32 | Die Qualität der Jpeg-Datei (0~100), 0 ist am niedrigsten und 100 ist am höchsten |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Speichert das Bild in einer Datei mit dem angegebenen Bildformat und der Qualität.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |
| format | ImageFormat | Das Format des Bildes. |
| quality | Int32 | Die Qualität der Jpeg-Datei (0~100), 0 ist am niedrigsten und 100 ist am höchsten |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Speichert das Bild in einer Datei mit der angegebenen Seitengröße, dem Bildformat und der Qualität.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateipfad und Name, um das Bild zu speichern. |
| pageSize | PageSize | Die Seitengröße des Bildes. |
| format | ImageFormat | Das Format des Bildes. |
| quality | Int32 | Die Qualität der Jpeg-Datei (0~100), 0 ist am niedrigsten und 100 ist am höchsten |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)