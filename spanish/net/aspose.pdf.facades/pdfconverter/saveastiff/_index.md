---
title: SaveAsTIFF
second_title: Referencia de API de Aspose.PDF para .NET
description: Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF.
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El archivo para guardar la imagen TIFF. |

### Ejemplos

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

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El archivo de salida. |
| compressionType | CompressionType | Tipo de la compresión. |

### Ejemplos

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

### Ver también

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un solo archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El nombre del archivo para guardar la imagen TIFF |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Convierte cada página de un documento pdf en imágenes con tamaño de página y guarda las imágenes en un solo archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El nombre del archivo para guardar la imagen TIFF |
| pageSize | PageSize | El tamaño de página de la imagen. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Convierte cada página de un documento pdf en imágenes con tamaño de página y guarda las imágenes en un solo archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El nombre del archivo para guardar la imagen TIFF |
| pageSize | PageSize | El tamaño de página de la imagen. |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un solo archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El nombre del archivo para guardar la imagen TIFF |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |
| compressionType | CompressionType | Tipo de la compresión. |

### Ver también

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un solo archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El nombre del archivo para guardar la imagen TIFF |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |

### Ver también

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en un solo archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El nombre del archivo para guardar la imagen TIFF |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |
| converter | IIndexBitmapConverter | Convertidor externo |

### Ver también

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Convierte cada página de un documento pdf en imágenes y las guarda en una sola secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | El flujo de salida. |
| compressionType | CompressionType | Tipo de la compresión. |

### Ver también

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Convierte cada página de un documento pdf en imágenes con tamaño de página y guarda las imágenes en una única secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |
| pageSize | PageSize | El tamaño de página de la imagen. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Convierte cada página de un documento pdf en imágenes con tamaño de página y guarda las imágenes en una única secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |
| pageSize | PageSize | El tamaño de página de la imagen. |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en una única secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en una única secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |
| compressionType | CompressionType | Tipo de la compresión. |

### Ver también

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en una única secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |

### Ver también

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Convierte cada página de un documento pdf en imágenes con dimensiones y guarda las imágenes en una única secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |
| converter | IIndexBitmapConverter | Convertidor externo |

### Ver también

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Convierte cada página de un documento pdf en imágenes y las guarda en un solo archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El nombre del archivo para guardar la imagen TIFF |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |

### Ver también

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Convierte cada página de un documento pdf en imágenes y las guarda en un solo archivo TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | El nombre del archivo para guardar la imagen TIFF |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |
| converter | IIndexBitmapConverter | Convertidor externo |

### Ver también

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Convierte cada página de un documento pdf en imágenes y las guarda en una sola secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |

### Ver también

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Convierte cada página de un documento pdf en imágenes y las guarda en una sola secuencia TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |
| settings | TiffSettings | Objeto de configuración que define los parámetros TIFF. |
| converter | IIndexBitmapConverter | Convertidor externo |

### Ver también

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
