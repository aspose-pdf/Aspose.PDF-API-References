---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Skapar linjeannotering
type: docs
weight: 180
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine metod

Skapar linjeannotering.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Annoteringsrektangeln som definierar platsen för annoteringen på sidan. |
| contents | String | Innehållet i annoteringen. |
| x1 | Single | Den startande horisontella koordinaten för linjen. |
| y1 | Single | Den startande vertikala koordinaten för linjen. |
| x2 | Single | Den avslutande horisontella koordinaten för linjen. |
| y2 | Single | Den avslutande vertikala koordinaten för linjen. |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| border | Int32 | Kantens bredd i punkter. Om detta värde är 0 ritas ingen kant. Standardvärdet är 1. |
| clr | Color | Färgen på linjen. |
| borderStyle | String | Kantstilen som specificerar bredden och streckmönstret som ska användas vid ritning av linjen. Detta värde kan vara: "S" (Solid), "D" (Streckad), "B" (Avfasad), "I" (Inskuren), "U" (Understruken). |
| dashArray | Int32[] | En streckarray som definierar ett mönster av streck och luckor som ska användas vid ritning av en streckad kant. Om det används måste borderStyle ställas in på "D". |
| LEArray | String[] | En array med två värden som respektive specificerar början och slutstil för ritlinjen. Värdena kan vara: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)