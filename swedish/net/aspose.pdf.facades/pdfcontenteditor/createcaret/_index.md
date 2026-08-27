---
title: "PdfContentEditor.CreateCaret"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor-metod. Skapar caret-annotation"
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret method

Skapar markörannotation.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| caretRect | Rectangle | De faktiska gränserna för den underliggande markören. |
| symbol | String | En symbol kommer att associeras med markören. Värdet kan vara: "P" (Paragraph), "None". |
| annotContents | String | Innehållet i annotationen. |
| color | Color | Färgen på annotationen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


