---
title: SaveAsTIFF
second_title: Aspose.PDF per .NET API Reference
description: Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF.
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il file per salvare l'immagine TIFF. |

### Esempi

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

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il file di output. |
| compressionType | CompressionType | Tipo di compressione. |

### Esempi

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

### Guarda anche

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il nome del file per salvare l'immagine TIFF |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Converte ogni pagina di un documento pdf in immagini con dimensione pagina e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il nome del file per salvare l'immagine TIFF |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Converte ogni pagina di un documento pdf in immagini con dimensione pagina e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il nome del file per salvare l'immagine TIFF |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il nome del file per salvare l'immagine TIFF |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| compressionType | CompressionType | Tipo di compressione. |

### Guarda anche

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il nome del file per salvare l'immagine TIFF |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |

### Guarda anche

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il nome del file per salvare l'immagine TIFF |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |
| converter | IIndexBitmapConverter | Convertitore esterno |

### Guarda anche

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso di output. |
| compressionType | CompressionType | Tipo di compressione. |

### Guarda anche

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Converte ogni pagina di un documento pdf in immagini con dimensione pagina e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Converte ogni pagina di un documento pdf in immagini con dimensione pagina e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| compressionType | CompressionType | Tipo di compressione. |

### Guarda anche

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |

### Guarda anche

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Converte ogni pagina di un documento pdf in immagini con dimensioni e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |
| converter | IIndexBitmapConverter | Convertitore esterno |

### Guarda anche

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Converte ogni pagina di un documento pdf in immagini con e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il nome del file per salvare l'immagine TIFF |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |

### Guarda anche

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Converte ogni pagina di un documento pdf in immagini con e salva le immagini in un unico file TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il nome del file per salvare l'immagine TIFF |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |
| converter | IIndexBitmapConverter | Convertitore esterno |

### Guarda anche

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |

### Guarda anche

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Converte ogni pagina di un documento pdf in immagini e salva le immagini in un unico flusso TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine TIFF. |
| settings | TiffSettings | Oggetto Impostazioni che definisce i parametri TIFF. |
| converter | IIndexBitmapConverter | Convertitore esterno |

### Guarda anche

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
