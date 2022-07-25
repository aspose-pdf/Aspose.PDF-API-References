---
title: GetNextImage
second_title: Aspose.PDF per .NET API Reference
description: Salva limmagine su file con il formato immagine predefinito - jpeg.
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Salva l'immagine su file con il formato immagine predefinito - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Salva l'immagine su file con le dimensioni della pagina specificate e il formato immagine predefinito - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Salva l'immagine su file con il formato immagine givin.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |

### Esempi

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

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Salva l'immagine su file con le dimensioni della pagina e il formato dell'immagine specificati.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| format | ImageFormat | Il formato dell'immagine. |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Salva l'immagine in streaming con il formato immagine predefinito - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Salva l'immagine in streaming con una determinata dimensione della pagina.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Salva l'immagine in streaming con il formato immagine specificato.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Salva l'immagine in streaming con una determinata dimensione della pagina.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| format | ImageFormat | Il formato dell'immagine. |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Salva l'immagine su file con il formato, le dimensioni e la qualità dell'immagine specificati.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è la più bassa e 100 è la più alta |

### Esempi

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

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Salva l'immagine per lo streaming con il formato, le dimensioni e la qualità dell'immagine givin.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è la più bassa e 100 è la più alta |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Salva l'immagine su file con il formato immagine, la dimensione e la qualità dell'immagine givin.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Double | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Double | L'altezza dell'immagine, l'unità è pixel.. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è la più bassa e 100 è la più alta |

### Esempi

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

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Salva l'immagine per lo streaming con il formato, le dimensioni e la qualità dell'immagine givin.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Double | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Double | L'altezza dell'immagine, l'unità è pixel. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è la più bassa e 100 è la più alta |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Salva l'immagine su file con il formato e le dimensioni dell'immagine specificati.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

### Esempi

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

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Salva l'immagine per lo streaming con il formato, le dimensioni e la qualità dell'immagine givin.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Salva l'immagine in streaming con il formato e la qualità dell'immagine specificati.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è la più bassa e 100 è la più alta |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Salva l'immagine per lo streaming con le dimensioni della pagina, il formato dell'immagine e la qualità specificati.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Il flusso per salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è la più bassa e 100 è la più alta |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Salva l'immagine su file con il formato e la qualità dell'immagine specificati.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è la più bassa e 100 è la più alta |

### Guarda anche

* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Salva l'immagine su file con le dimensioni della pagina, il formato dell'immagine e la qualità specificati.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file per salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è la più bassa e 100 è la più alta |

### Guarda anche

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfconverter)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
