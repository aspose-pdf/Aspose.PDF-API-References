---
title: ExtractLink
second_title: Referencia de API de Aspose.PDF para .NET
description: Extrae la colección de instancias de enlace contenidas en el documento PDF.
type: docs
weight: 370
url: /es/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

Extrae la colección de instancias de enlace contenidas en el documento PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Valor_devuelto

La colección de objetos Link

### Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // trabajar con instancia de enlace
}
```

### Ver también

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
