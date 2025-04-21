---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Recupera la siguiente imagen del documento PDF. Nota ExtractImage debe ser llamado antes de usar este método
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Recupera la siguiente imagen del documento PDF. Nota: ExtractImage debe ser llamado antes de usar este método.

```csharp
public bool GetNextImage(string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | String | Archivo donde se almacenará la imagen |

### Valor de Retorno

True si la imagen se extrae con éxito

## Ejemplos

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Recupera la siguiente imagen del documento PDF con el formato de imagen dado. Nota: ExtractImage debe ser llamado antes de usar este método.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | String | Archivo donde se almacenará la imagen |
| format | ImageFormat | El formato de la imagen. |

### Valor de Retorno

True si la imagen se extrae con éxito

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Recupera la siguiente imagen del archivo PDF y la almacena en el flujo con el formato de imagen dado.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | Flujo donde se guardarán los datos de la imagen |
| format | ImageFormat | El formato de la imagen. |

### Valor de Retorno

True en caso de que la imagen se extraiga con éxito.

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Recupera la siguiente imagen del archivo PDF y la almacena en el flujo.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | Flujo donde se guardarán los datos de la imagen |

### Valor de Retorno

True en caso de que la imagen se extraiga con éxito.

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)