---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Skapar kvadratcirkel-annotering
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle metod

Skapar kvadrat-cirkel-annotering.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Annoteringsrektangeln som definierar platsen för annoteringen på sidan. |
| contents | String | Innehållet i annoteringen. |
| clr | Color | Färgen på kvadraten eller cirkeln. |
| square | Boolean | Sant (kvadrat), falskt (cirkel). |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| borderWidth | Int32 | Kantbredden på kvadraten eller cirkeln. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)