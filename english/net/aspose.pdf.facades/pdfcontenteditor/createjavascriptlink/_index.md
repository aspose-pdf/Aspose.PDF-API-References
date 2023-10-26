---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Creates a link to JavaScript in PDF document
type: docs
weight: 170
url: /net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

Creates a link to JavaScript in PDF document.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| code | String | The JavaScript code. |
| rect | Rectangle | The rectangle for active click. |
| originalPage | Int32 | The number of original page where rectangle bound with link will be created. |
| color | Color | The colour of rectangle for active click. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


