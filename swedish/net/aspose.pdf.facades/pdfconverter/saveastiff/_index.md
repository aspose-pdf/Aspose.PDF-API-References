---
title: SaveAsTIFF
second_title: Aspose.PDF för .NET API Referens
description: Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-fil.
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filen för att spara TIFF-bilden. |

### Exempel

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

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Utdatafilen. |
| compressionType | CompressionType | Typ av kompression. |

### Exempel

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

### Se även

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filnamnet för att spara TIFF-bilden |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filnamnet för att spara TIFF-bilden |
| pageSize | PageSize | Bildens sidstorlek. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filnamnet för att spara TIFF-bilden |
| pageSize | PageSize | Bildens sidstorlek. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filnamnet för att spara TIFF-bilden |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |
| compressionType | CompressionType | Typ av kompression. |

### Se även

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filnamnet för att spara TIFF-bilden |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se även

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filnamnet för att spara TIFF-bilden |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |
| converter | IIndexBitmapConverter | Extern omvandlare |

### Se även

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Utgångsströmmen. |
| compressionType | CompressionType | Typ av kompression. |

### Se även

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilder i en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |
| pageSize | PageSize | Bildens sidstorlek. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Konverterar varje sida i ett pdf-dokument till bilder med sidstorlek och sparar bilder i en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |
| pageSize | PageSize | Bildens sidstorlek. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se även

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder i en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |

### Se även

* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder i en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |
| compressionType | CompressionType | Typ av kompression. |

### Se även

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder i en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se även

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Konverterar varje sida i ett pdf-dokument till bilder med dimensioner och sparar bilder i en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildhöjden, enheten är pixel. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |
| converter | IIndexBitmapConverter | Extern omvandlare |

### Se även

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Konverterar varje sida i ett pdf-dokument till bilder med och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filnamnet för att spara TIFF-bilden |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se även

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Konverterar varje sida i ett pdf-dokument till bilder med och sparar bilder till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | String | Filnamnet för att spara TIFF-bilden |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |
| converter | IIndexBitmapConverter | Extern omvandlare |

### Se även

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se även

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Konverterar varje sida i ett pdf-dokument till bilder och sparar bilder till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Stream | Streamen för att spara TIFF-bilden. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |
| converter | IIndexBitmapConverter | Extern omvandlare |

### Se även

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namnutrymme [Aspose.Pdf.Facades](../../pdfconverter)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
