---
title: GetNextImage
second_title: Referencia de API de Aspose.PDF para .NET
description: Recupera la imagen siguiente del documento PDF. Nota se debe llamar a ExtractImage antes de usar este método.
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Recupera la imagen siguiente del documento PDF. Nota: se debe llamar a ExtractImage antes de usar este método.

```csharp
public bool GetNextImage(string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | Archivo donde se almacenará la imagen |

### Valor_devuelto

Cierto es que la imagen se extrajo con éxito

### Ejemplos

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

### Ver también

* class [PdfExtractor](../../pdfextractor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfextractor)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Recupera la siguiente imagen del documento PDF con el formato de imagen dado. Nota: se debe llamar a ExtractImage antes de usar este método.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputFile | String | Archivo donde se almacenará la imagen |
| format | ImageFormat | El formato de la imagen. |

### Valor_devuelto

Cierto es que la imagen se extrajo con éxito

### Ver también

* class [PdfExtractor](../../pdfextractor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfextractor)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Recupera la siguiente imagen del archivo PDF y la almacena en el flujo con el formato de imagen dado.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | Transmisión donde se guardarán los datos de la imagen |
| format | ImageFormat | El formato de la imagen. |

### Valor_devuelto

True en caso de que la imagen se extraiga correctamente.

### Ver también

* class [PdfExtractor](../../pdfextractor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfextractor)
* asamblea [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Recupera la siguiente imagen del archivo PDF y la almacena en la secuencia.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputStream | Stream | Transmisión donde se guardarán los datos de la imagen |

### Valor_devuelto

True en caso de que la imagen se extraiga correctamente.

### Ver también

* class [PdfExtractor](../../pdfextractor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfextractor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->