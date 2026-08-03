---
title: "PdfContentEditor.DeleteAttachments"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Raderar alla bilagor i PDF-dokument"
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/deleteattachments/
---
## PdfContentEditor.DeleteAttachments method

Tar bort alla bilagor i PDF-dokument.

```csharp
public void DeleteAttachments()
```

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteAttachments();
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


