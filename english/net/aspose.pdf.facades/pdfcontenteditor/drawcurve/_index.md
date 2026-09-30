---
title: "PdfContentEditor.DrawCurve"
linktitle: "DrawCurve"
articleTitle: "DrawCurve"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates curve annotation."
type: docs
weight: 320
url: "/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/"
product_version: "26.9.0"
---
## PdfContentEditor.DrawCurve method

Creates curve annotation.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| lineInfo | LineInfo | The instance of LineInfo class. |
| page | Int32 | The number of original page where the annotation will be created. |
| annotRect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| annotContents | String | The contents of the annotation. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### See Also

* class [LineInfo](../../../aspose.pdf.facades/lineinfo/)
* class [Rectangle](../../../aspose.pdf.drawing/rectangle/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

