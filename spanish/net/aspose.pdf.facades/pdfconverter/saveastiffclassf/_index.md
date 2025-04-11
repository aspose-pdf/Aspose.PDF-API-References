---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: Método PdfConverter. Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un solo archivo TIFF ClassF
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un solo archivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | String | El flujo para guardar la imagen TIFF. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es píxel. |

## Ejemplos

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

### Ver También

* clase [PdfConverter](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un solo archivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | String | El flujo para guardar la imagen TIFF. |
| pageSize | PageSize | El tamaño de la página de la imagen. |

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfConverter](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un solo flujo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | El flujo para guardar la imagen TIFF. |
| imageWidth | Int32 | El ancho de la imagen, la unidad es píxel. |
| imageHeight | Int32 | La altura de la imagen, la unidad es píxel. |

### Ver También

* clase [PdfConverter](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un solo flujo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | El flujo para guardar la imagen TIFF. |
| pageSize | PageSize | El tamaño de la página de la imagen. |

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfConverter](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un solo archivo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | String | El flujo para guardar la imagen TIFF. |

## Ejemplos

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

### Ver También

* clase [PdfConverter](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Convierte cada página de un documento pdf en imágenes y guarda las imágenes en un solo flujo TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | El flujo para guardar la imagen TIFF. |

### Ver También

* clase [PdfConverter](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)