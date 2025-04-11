---
title: PdfContentEditor.CreatePolyLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Skapar polyline-annotering
type: docs
weight: 240
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## PdfContentEditor.CreatePolyLine metod

Skapar polyline-annotering.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lineInfo | LineInfo | Instansen av LineInfo-klassen. |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| annotRect | Rectangle | Annoteringsrektangeln som definierar platsen för annoteringen på sidan. |
| annotContents | String | Innehållet i annoteringen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Se Även

* klass [LineInfo](../../lineinfo/)
* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)