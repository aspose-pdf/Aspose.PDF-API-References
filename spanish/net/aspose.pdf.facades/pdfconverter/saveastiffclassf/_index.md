---
title: SaveAsTIFFClassF
second_title: Referencia de API de Aspose.PDF para .NET
description: Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF ClassF.
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La secuencia para guardar la imagen TIFF. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es el píxel. |

### Ejemplos

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La secuencia para guardar la imagen TIFF. |
| pageSize | PageSize | El tamaño de página de la imagen. |

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Convierte cada página de un documento pdf en imágenes y las guarda en una única secuencia TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
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

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Convierte cada página de un documento pdf en imágenes y las guarda en una única secuencia TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
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

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Convierte cada página de un documento pdf en imágenes y las guarda en un único archivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | La secuencia para guardar la imagen TIFF. |

### Ejemplos

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Convierte cada página de un documento pdf en imágenes y las guarda en una única secuencia TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | La secuencia para guardar la imagen TIFF. |

### Ver también

* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
