---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Tar bort öppningsåtgärd från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder explicit 'GoTo'-åtgärd vid start.
type: docs
weight: 430
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction metod

Tar bort öppningsåtgärd från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder explicit 'GoTo'-åtgärd vid start.

```csharp
public void RemoveDocumentOpenAction()
```

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)