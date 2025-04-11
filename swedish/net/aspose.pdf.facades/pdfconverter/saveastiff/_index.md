---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: PdfConverter metod. Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-fil
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filen för att spara TIFF-bilden. |

## Exempel

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

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Utdatafilen. |
| compressionType | CompressionType | Typ av kompression. |

## Exempel

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

### Se Även

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Konverterar varje sida av ett pdf-dokument till bilder med dimensioner, och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filnamnet för att spara TIFF-bilden |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Konverterar varje sida av ett pdf-dokument till bilder med sidstorlek och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filnamnet för att spara TIFF-bilden |
| pageSize | PageSize | Sidstorleken för bilden. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Konverterar varje sida av ett pdf-dokument till bilder med sidstorlek och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filnamnet för att spara TIFF-bilden |
| pageSize | PageSize | Sidstorleken för bilden. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Konverterar varje sida av ett pdf-dokument till bilder med dimensioner, och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filnamnet för att spara TIFF-bilden |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| compressionType | CompressionType | Typ av kompression. |

### Se Även

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Konverterar varje sida av ett pdf-dokument till bilder med dimensioner, och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filnamnet för att spara TIFF-bilden |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se Även

* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Konverterar varje sida av ett pdf-dokument till bilder med dimensioner, och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filnamnet för att spara TIFF-bilden |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |
| converter | IIndexBitmapConverter | Extern konverterare |

### Se Även

* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Utdataströmmen. |
| compressionType | CompressionType | Typ av kompression. |

### Se Även

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Konverterar varje sida av ett pdf-dokument till bilder med sidstorlek och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Konverterar varje sida av ett pdf-dokument till bilder med sidstorlek och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| pageSize | PageSize | Sidstorleken för bilden. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Konverterar varje sida av ett pdf-dokument till bilder med dimensioner, och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |

### Se Även

* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Konverterar varje sida av ett pdf-dokument till bilder med dimensioner, och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| compressionType | CompressionType | Typ av kompression. |

### Se Även

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Konverterar varje sida av ett pdf-dokument till bilder med dimensioner, och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se Även

* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Konverterar varje sida av ett pdf-dokument till bilder med dimensioner, och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| imageWidth | Int32 | Bildens bredd, enheten är pixel. |
| imageHeight | Int32 | Bildens höjd, enheten är pixel. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |
| converter | IIndexBitmapConverter | Extern konverterare |

### Se Även

* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filnamnet för att spara TIFF-bilden |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se Även

* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-fil.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFile | Sträng | Filnamnet för att spara TIFF-bilden |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |
| converter | IIndexBitmapConverter | Extern konverterare |

### Se Även

* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |

### Se Även

* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Konverterar varje sida av ett pdf-dokument till bilder och sparar bilderna till en enda TIFF-ström.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputStream | Ström | Strömmen för att spara TIFF-bilden. |
| settings | TiffSettings | Inställningsobjekt som definierar TIFF-parametrar. |
| converter | IIndexBitmapConverter | Extern konverterare |

### Se Även

* klass [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* klass [PdfConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)