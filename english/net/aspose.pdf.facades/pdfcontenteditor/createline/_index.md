---
title: "PdfContentEditor.CreateLine"
linktitle: "CreateLine"
articleTitle: "CreateLine"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Creates line annotation."
type: docs
weight: 300
url: "/net/aspose.pdf.facades/pdfcontenteditor/createline/"
product_version: "26.9.0"
---
## CreateLine([Rectangle](../../../aspose.pdf.drawing/rectangle/), string, float, float, float, float, int, int, [Color](../../../aspose.pdf/color/), string, int[], string[]) {#createline}

Creates line annotation.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | string | The contents of the annotation. |
| x1 | float | The starting horizontal coordinate of the line. |
| y1 | float | The starting vertical coordinate of the line. |
| x2 | float | The ending horizontal coordinate of the line. |
| y2 | float | The ending vertical coordinate of the line. |
| page | int | The number of original page where the annotation will be created. |
| border | int | The border width in points. If this value is 0 no border is drawn. Default value is 1. |
| clr | Color | The color of line. |
| borderStyle | string | The border style specifying the width and dash pattern to be used in drawing the line.
 This value can be: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | int[] | A dash array defining a pattern of dashes and gaps to be used in drawing a dashed border.
 If it is used, borderSyle must be accordingly set to "D". |
| LEArray | string[] | An array of two values respectively specifying the beginning and ending style of the drawing line.
 The values can be: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

