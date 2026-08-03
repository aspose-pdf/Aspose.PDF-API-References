---
title: "`PdfContentEditor.CreateSquareCircle`"
second_title: "Aspose.PDF för .NET API‑referens"
description: "`PdfContentEditor`-metod. Skapar en fyrkant/cirkel-anteckning"
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

Skapar fyrkant-cirkel-annotation.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| innehåll | String | Innehållet i annotationen. |
| clr | Color | Färgen på fyrkanten eller cirkeln. |
| square | Boolean | Sant (square), falskt (sircle). |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| borderWidth | Int32 | Kantbredden på fyrkant eller cirkel. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


