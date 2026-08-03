---
title: "PdfContentEditor.RemoveDocumentOpenAction"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor‑metod. Tar bort öppningsåtgärd från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder en explicit GoTo‑åtgärd vid start."
type: docs
weight: 430
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

Tar bort öppningsåtgärden från dokumentet. Denna operation är användbar när man sammanfogar flera dokument som använder en explicit 'GoTo'-åtgärd vid start.

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

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


