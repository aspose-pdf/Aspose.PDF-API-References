---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Extrae la colección de instancias de Link contenidas en el documento PDF
type: docs
weight: 370
url: /es/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## Método PdfContentEditor.ExtractLink

Extrae la colección de instancias de Link contenidas en el documento PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Valor de Retorno

La colección de objetos Link

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // work with Link instance
}
```

### Ver También

* clase [Annotation](../../../aspose.pdf.annotations/annotation/)
* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)