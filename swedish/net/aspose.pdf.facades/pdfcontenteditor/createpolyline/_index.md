---
title: "`PdfContentEditor.CreatePolyLine`"
second_title: "Aspose.PDF för .NET API‑referens"
description: "`PdfContentEditor`-metod. Skapar en polylinjeanteckning"
type: docs
weight: 240
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## PdfContentEditor.CreatePolyLine method

Skapar polylinjeannotation.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lineInfo | LineInfo | Instansen av LineInfo-klassen. |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| annotContents | String | Innehållet i annotationen. |

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

### Se även

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


