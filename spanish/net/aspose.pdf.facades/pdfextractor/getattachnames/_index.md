---
title: GetAttachNames
second_title: Referencia de API de Aspose.PDF para .NET
description: Devuelve una lista de archivos adjuntos en un archivo PDF. Nota se debe llamar a ExtractAttachments antes de usar este método.
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

Devuelve una lista de archivos adjuntos en un archivo PDF. Nota: se debe llamar a ExtractAttachments antes de usar este método.

```csharp
public IList<string> GetAttachNames()
```

### Valor_devuelto

Lista de archivos adjuntos

### Ejemplos

El ejemplo demuestra cómo extraer los nombres de los archivos adjuntos de un archivo PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Ver también

* class [PdfExtractor](../../pdfextractor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfextractor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->