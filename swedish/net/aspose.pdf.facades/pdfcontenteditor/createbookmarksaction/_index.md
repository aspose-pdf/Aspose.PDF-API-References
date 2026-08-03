---
title: "PdfContentEditor.CreateBookmarksAction"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Skapar ett bokmärke med den angivna åtgärden"
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction method

Skapar ett bokmärke med den angivna åtgärden.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| titel | String | Bokmärkets titel. |
| color | Color | Färgen på bokmärkets titel. |
| boldFlag | Boolean | Flaggan för fet attribut. |
| italicFlag | Boolean | Flaggan för kursiv attribut. |
| fil | String | En annan fil eller applikation som krävs när åtgärdstypen är "GoToR" eller "Launch". |
| actionType | String | Åtgärdstypen. Värdet kan vara: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | Den lokala destinationen eller fjärrdestinationen eller URL:en. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


