---
title: "PdfContentEditor.CreateLine"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor method. Skapar linjeanteckning"
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

Skapar linjeannotation.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| innehåll | String | Innehållet i annotationen. |
| x1 | Single | Den horisontella startkoordinaten för linjen. |
| y1 | Single | Den vertikala startkoordinaten för linjen. |
| x2 | Single | Den horisontella slutkoordinaten för linjen. |
| y2 | Single | Den vertikala slutkoordinaten för linjen. |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| border | Int32 | Kantens bredd i punkter. Om detta värde är 0 ritas ingen kant. Standardvärdet är 1. |
| clr | Color | Färgen på linjen. |
| borderStyle | String | Kantstilen som specificerar bredden och streckmönstret som ska användas vid ritning av linjen. Detta värde kan vara: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | Int32[] | En dash-array som definierar ett mönster av streck och mellanrum som ska användas vid ritning av en streckad kant. Om den används måste borderSyle sättas till "D". |
| LEArray | String[] | En array med två värden som respektive specificerar början och slutstil för den ritade linjen. Värdena kan vara: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


