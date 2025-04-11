---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Skapar ett bokmärke med den angivna åtgärden
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction metod

Skapar ett bokmärke med den angivna åtgärden.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| title | Sträng | Titeln på bokmärket. |
| color | Färg | Färgen på bokmärkets titel. |
| boldFlag | Boolean | Flaggan för fet stil. |
| italicFlag | Boolean | Flaggan för kursiv stil. |
| file | Sträng | En annan fil eller applikation som krävs när åtgärdstypen är "GoToR" eller "Launch". |
| actionType | Sträng | Åtgärdstypen. Värdet kan vara: "GoToR", "Launch", "GoTo", "URI". |
| destination | Sträng | Den lokala destinationen eller den fjärrdestinationen eller URL. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)