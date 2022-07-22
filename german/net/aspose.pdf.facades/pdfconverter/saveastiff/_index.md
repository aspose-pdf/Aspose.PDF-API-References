---
title: SaveAsTIFF
second_title: Aspose.PDF für .NET-API-Referenz
description: Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-Datei.
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Die Datei zum Speichern des TIFF-Bildes. |

### Beispiele

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

* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Die Ausgabedatei. |
| compressionType | CompressionType | Art der Kompression. |

### Beispiele

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

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname zum Speichern des TIFF-Bildes |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |

### Siehe auch

* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname zum Speichern des TIFF-Bildes |
| pageSize | PageSize | Die Seitengröße des Bildes. |

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname zum Speichern des TIFF-Bildes |
| pageSize | PageSize | Die Seitengröße des Bildes. |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname zum Speichern des TIFF-Bildes |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| compressionType | CompressionType | Art der Kompression. |

### Siehe auch

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname zum Speichern des TIFF-Bildes |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |

### Siehe auch

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname zum Speichern des TIFF-Bildes |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |
| converter | IIndexBitmapConverter | Externer Konverter |

### Siehe auch

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |

### Siehe auch

* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Ausgangsstrom. |
| compressionType | CompressionType | Art der Kompression. |

### Siehe auch

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |
| pageSize | PageSize | Die Seitengröße des Bildes. |

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Seitengröße und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |
| pageSize | PageSize | Die Seitengröße des Bildes. |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |

### Siehe auch

* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| compressionType | CompressionType | Art der Kompression. |

### Siehe auch

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |

### Siehe auch

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit Abmessungen und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |
| imageWidth | Int32 | Die Bildbreite, die Einheit ist Pixel. |
| imageHeight | Int32 | Die Bildhöhe, die Einheit ist Pixel. |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |
| converter | IIndexBitmapConverter | Externer Konverter |

### Siehe auch

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname zum Speichern des TIFF-Bildes |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |

### Siehe auch

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Konvertiert jede Seite eines PDF-Dokuments in Bilder mit und speichert Bilder in einer einzigen TIFF-Datei.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | String | Der Dateiname zum Speichern des TIFF-Bildes |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |
| converter | IIndexBitmapConverter | Externer Konverter |

### Siehe auch

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |

### Siehe auch

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Konvertiert jede Seite eines PDF-Dokuments in Bilder und speichert Bilder in einem einzigen TIFF-Stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStream | Stream | Der Stream zum Speichern des TIFF-Bilds. |
| settings | TiffSettings | Einstellungsobjekt, das TIFF-Parameter definiert. |
| converter | IIndexBitmapConverter | Externer Konverter |

### Siehe auch

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namensraum [Aspose.Pdf.Facades](../../pdfconverter)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
