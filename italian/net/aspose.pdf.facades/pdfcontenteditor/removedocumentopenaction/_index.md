---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit GoTo action on startup
type: docs
weight: 430
url: /it/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## Metodo PdfContentEditor.RemoveDocumentOpenAction

Rimuove l'azione di apertura dal documento. Questa operazione è utile quando si concatenano più documenti che utilizzano un'azione 'GoTo' esplicita all'avvio.

```csharp
public void RemoveDocumentOpenAction()
```

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)