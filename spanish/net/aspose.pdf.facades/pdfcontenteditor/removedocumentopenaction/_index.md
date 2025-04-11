---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Elimina la acción de apertura del documento. Esta operación es útil al concatenar múltiples documentos que utilizan una acción 'GoTo' explícita al inicio.
type: docs
weight: 430
url: /es/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## Método PdfContentEditor.RemoveDocumentOpenAction

Elimina la acción de apertura del documento. Esta operación es útil al concatenar múltiples documentos que utilizan una acción 'GoTo' explícita al inicio.

```csharp
public void RemoveDocumentOpenAction()
```

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)