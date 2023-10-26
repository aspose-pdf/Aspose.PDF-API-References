---
title: PdfContentEditor.CreatePolygon
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Creates polygon annotation
type: docs
weight: 230
url: /net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## PdfContentEditor.CreatePolygon method

Creates polygon annotation.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### See Also

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


