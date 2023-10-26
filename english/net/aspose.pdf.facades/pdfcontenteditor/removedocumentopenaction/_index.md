---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit GoTo action on startup
type: docs
weight: 430
url: /net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit 'GoTo' action on startup.

```csharp
public void RemoveDocumentOpenAction()
```

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


