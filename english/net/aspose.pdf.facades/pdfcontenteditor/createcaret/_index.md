---
title: "PdfContentEditor.CreateCaret"
linktitle: "CreateCaret"
articleTitle: "CreateCaret"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates caret annotation."
type: docs
weight: 350
url: "/net/aspose.pdf.facades/pdfcontenteditor/createcaret/"
product_version: "26.9.0"
---
## PdfContentEditor.CreateCaret method

Creates caret annotation.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| caretRect | Rectangle | The actual boundaries of the underlying caret. |
| symbol | String | A symbol will be associated with the caret. Value can be: "P" (Paragraph), "None". |
| annotContents | String | The contents of the annotation. |
| color | Color | The color of the annotation. |

### See Also

* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [Color](../../../aspose.pdf/color/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

