---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Skapar kurvanmärkning
type: docs
weight: 360
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve metod

Skapar kurvanmärkning.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lineInfo | LineInfo | Instansen av LineInfo-klassen. |
| page | Int32 | Numret på den ursprungliga sidan där anmärkningen kommer att skapas. |
| annotRect | Rectangle | Anmärkningens rektangel som definierar platsen för anmärkningen på sidan. |
| annotContents | String | Innehållet i anmärkningen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Se Även

* klass [LineInfo](../../lineinfo/)
* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)