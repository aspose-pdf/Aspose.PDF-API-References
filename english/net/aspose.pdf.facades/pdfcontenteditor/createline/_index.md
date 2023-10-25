---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Creates line annotation
type: docs
weight: 180
url: /net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

Creates line annotation.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | The annotation rectangle defining the location of the annotation on the page. |
| contents | String | The contents of the annotation. |
| x1 | Single | The starting horizontal coordinate of the line. |
| y1 | Single | The starting vertical coordinate of the line. |
| x2 | Single | The ending horizontal coordinate of the line. |
| y2 | Single | The ending vertical coordinate of the line. |
| page | Int32 | The number of original page where the annotation will be created. |
| border | Int32 | The border width in points. If this value is 0 no border is drawn. Default value is 1. |
| clr | Color | The color of line. |
| borderStyle | String | The border style specifying the width and dash pattern to be used in drawing the line. This value can be: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | Int32[] | A dash array defining a pattern of dashes and gaps to be used in drawing a dashed border. If it is used, borderSyle must be accordingly set to "D". |
| LEArray | String[] | An array of two values respectively specifying the beginning and ending style of the drawing line. The values can be: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


