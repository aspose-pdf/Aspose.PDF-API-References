---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Devuelve una lista de archivos adjuntos en el archivo PDF. Nota ExtractAttachments debe ser llamado antes de usar este método
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## Método PdfExtractor.GetAttachNames

Devuelve una lista de archivos adjuntos en el archivo PDF. Nota: ExtractAttachments debe ser llamado antes de usar este método.

```csharp
public IList<string> GetAttachNames()
```

### Valor de Retorno

Lista de archivos adjuntos

## Ejemplos

El ejemplo demuestra cómo extraer los nombres de los archivos adjuntos del archivo PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)