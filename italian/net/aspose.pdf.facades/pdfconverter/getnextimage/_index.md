---
title: PdfConverter.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfConverter. Salva l'immagine su file con formato immagine predefinito jpeg
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Salva l'immagine su file con formato immagine predefinito - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Salva l'immagine su file con la dimensione della pagina data e formato immagine predefinito - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### Vedi Anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Salva l'immagine su file con il formato immagine dato.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |

## Esempi

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

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Salva l'immagine su file con la dimensione della pagina e il formato immagine dati.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| format | ImageFormat | Il formato dell'immagine. |

### Vedi Anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Salva l'immagine su stream con formato immagine predefinito - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Salva l'immagine su stream con la dimensione della pagina data.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |

### Vedi Anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Salva l'immagine su stream con il formato immagine dato.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Salva l'immagine su stream con la dimensione della pagina e il formato immagine dati.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| format | ImageFormat | Il formato dell'immagine. |

### Vedi Anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Salva l'immagine su file con il formato immagine, le dimensioni e la qualità dati.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è il più basso e 100 è il più alto |

## Esempi

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

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Salva l'immagine su stream con il formato immagine, le dimensioni e la qualità dati.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è il più basso e 100 è il più alto |

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Salva l'immagine su file con il formato immagine, la dimensione dell'immagine e la qualità dati.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Double | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Double | L'altezza dell'immagine, l'unità è pixel. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è il più basso e 100 è il più alto |

## Esempi

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

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Salva l'immagine su stream con il formato immagine, la dimensione e la qualità dati.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Double | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Double | L'altezza dell'immagine, l'unità è pixel. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è il più basso e 100 è il più alto |

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Salva l'immagine su file con il formato immagine e le dimensioni dati.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

## Esempi

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

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Salva l'immagine su stream con il formato immagine, la dimensione e la qualità dati.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| imageWidth | Int32 | La larghezza dell'immagine, l'unità è pixel. |
| imageHeight | Int32 | L'altezza dell'immagine, l'unità è pixel. |

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Salva l'immagine su stream con il formato immagine e la qualità dati.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è il più basso e 100 è il più alto |

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Salva l'immagine su stream con la dimensione della pagina, il formato immagine e la qualità dati.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Lo stream in cui salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è il più basso e 100 è il più alto |

### Vedi Anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Salva l'immagine su file con il formato immagine e la qualità dati.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è il più basso e 100 è il più alto |

### Vedi Anche

* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Salva l'immagine su file con la dimensione della pagina, il formato immagine e la qualità dati.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | Il percorso e il nome del file in cui salvare l'immagine. |
| pageSize | PageSize | La dimensione della pagina dell'immagine. |
| format | ImageFormat | Il formato dell'immagine. |
| quality | Int32 | La qualità del file Jpeg (0~100), 0 è il più basso e 100 è il più alto |

### Vedi Anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)