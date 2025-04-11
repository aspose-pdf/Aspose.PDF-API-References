---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Elimina múltiples sellos en la página especificada por índices de sello
type: docs
weight: 330
url: /es/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## Método PdfContentEditor.DeleteStamp

Elimina múltiples sellos en la página especificada por índices de sello.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | Int32 | Número de página donde se eliminará el sello. |
| index | Int32[] | Índices de sello. |

## Ejemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Véase también

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)