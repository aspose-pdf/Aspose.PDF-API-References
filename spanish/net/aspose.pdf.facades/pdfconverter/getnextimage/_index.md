---
title: GetNextImage
second_title: Referencia de API de Aspose.PDF para .NET
description: Guarda la imagen en un archivo con el formato de imagen predeterminado jpeg.
type: docs
weight: 140
url: /es/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Guarda la imagen en un archivo con el formato de imagen predeterminado: jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Guarda la imagen en un archivo con el tamaño de página dado y el formato de imagen predeterminado: jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |
| pageSize | PageSize | El tamaño de página de la imagen. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Guarda la imagen en un archivo con el formato de imagen dado.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |

### Ejemplos

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

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Guarda la imagen en un archivo con el tamaño de página y el formato de imagen dados.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |
| pageSize | PageSize | El tamaño de página de la imagen. |
| format | ImageFormat | El formato de la imagen. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Guarda la imagen para transmitir con el formato de imagen predeterminado: jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Guarda la imagen para transmitir con el tamaño de página dado.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |
| pageSize | PageSize | El tamaño de página de la imagen. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Guarda la imagen para transmitir con el formato de imagen dado.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Guarda la imagen para transmitir con el tamaño de página dado.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |
| pageSize | PageSize | El tamaño de página de la imagen. |
| format | ImageFormat | El formato de la imagen. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Guarda la imagen en un archivo con el formato de imagen, las dimensiones y la calidad especificados.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |
| quality | Int32 | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

### Ejemplos

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

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Guarda la imagen para transmitir con el formato, las dimensiones y la calidad de la imagen dada.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |
| quality | Int32 | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Guarda la imagen en un archivo con el formato, el tamaño y la calidad de la imagen dados.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |
| imageWidth | Double | El ancho de la imagen, la unidad es píxeles. |
| imageHeight | Double | La altura de la imagen, la unidad son los píxeles. |
| quality | Int32 | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

### Ejemplos

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

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Guarda la imagen para transmitir con el formato, tamaño y calidad de imagen dados.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |
| imageWidth | Double | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Double | La altura de la imagen, la unidad es el píxel. |
| quality | Int32 | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Guarda la imagen en un archivo con el formato de imagen y las dimensiones dadas.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |

### Ejemplos

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

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Guarda la imagen para transmitir con el formato, tamaño y calidad de imagen dados.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Guarda la imagen para transmitir con el formato y la calidad de imagen dados.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |
| quality | Int32 | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Guarda la imagen para transmitir con el tamaño de página, el formato de imagen y la calidad determinados.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen. |
| pageSize | PageSize | El tamaño de página de la imagen. |
| format | ImageFormat | El formato de la imagen. |
| quality | Int32 | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Guarda la imagen en un archivo con el formato y la calidad de imagen dados.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |
| format | ImageFormat | El formato de la imagen. |
| quality | Int32 | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Guarda la imagen en un archivo con el tamaño de página, el formato de imagen y la calidad determinados.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La ruta del archivo y el nombre para guardar la imagen. |
| pageSize | PageSize | El tamaño de página de la imagen. |
| format | ImageFormat | El formato de la imagen. |
| quality | Int32 | La calidad del archivo Jpeg (0~100), 0 es la más baja y 100 es la más alta |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
