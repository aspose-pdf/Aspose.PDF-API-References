---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Adds additional action for document event
type: docs
weight: 60
url: /net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

Adds additional action for document event.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parameter | Type | Description |
| --- | --- | --- |
| eventType | String | The document event types. |
| code | String | The code of JavaScript. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


