---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter-Methode. Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Die Datei, in der das TIFF-Bild gespeichert werden soll. |

## Beispiele

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

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Die Ausgabedatei. |
| compressionType | CompressionType | Art der Kompression. |

## Beispiele

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

### Siehe auch

* Enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname, um das TIFF-Bild zu speichern |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitenformat und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname, um das TIFF-Bild zu speichern |
| pageSize | PageSize | Das Seitenformat des Bildes. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitenformat und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname, um das TIFF-Bild zu speichern |
| pageSize | PageSize | Das Seitenformat des Bildes. |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname, um das TIFF-Bild zu speichern |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| compressionType | CompressionType | Art der Kompression. |

### Siehe auch

* Enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname, um das TIFF-Bild zu speichern |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |

### Siehe auch

* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname, um das TIFF-Bild zu speichern |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |
| converter | IIndexBitmapConverter | Externer Konverter |

### Siehe auch

* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Schnittstelle [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Ausgabestream. |
| compressionType | CompressionType | Art der Kompression. |

### Siehe auch

* Enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitenformat und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| pageSize | PageSize | Das Seitenformat des Bildes. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitenformat und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| pageSize | PageSize | Das Seitenformat des Bildes. |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |

### Siehe auch

* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| compressionType | CompressionType | Art der Kompression. |

### Siehe auch

* Enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |

### Siehe auch

* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |
| converter | IIndexBitmapConverter | Externer Konverter |

### Siehe auch

* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Schnittstelle [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname, um das TIFF-Bild zu speichern |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |

### Siehe auch

* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einer einzelnen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname, um das TIFF-Bild zu speichern |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |
| converter | IIndexBitmapConverter | Externer Konverter |

### Siehe auch

* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Schnittstelle [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |

### Siehe auch

* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert die Bilder in einem einzelnen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream, um das TIFF-Bild zu speichern. |
| settings | TiffSettings | Einstellungsobjekt, das die TIFF-Parameter definiert. |
| converter | IIndexBitmapConverter | Externer Konverter |

### Siehe auch

* Klasse [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* Schnittstelle [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* Klasse [PdfConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)