---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Skapar markörannotering
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret metod

Skapar markörannotering.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| annotRect | Rectangle | Annoteringsrektangeln som definierar platsen för annoteringen på sidan. |
| caretRect | Rectangle | De faktiska gränserna för den underliggande markören. |
| symbol | String | En symbol kommer att kopplas till markören. Värdet kan vara: "P" (Stycke), "None". |
| annotContents | String | Innehållet i annoteringen. |
| color | Color | Färgen på annoteringen. |

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

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)