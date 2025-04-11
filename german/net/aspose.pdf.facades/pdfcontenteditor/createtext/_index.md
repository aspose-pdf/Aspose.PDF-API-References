---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Textanmerkung im PDF-Dokument
type: docs
weight: 290
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText-Methode

Erstellt eine Textanmerkung im PDF-Dokument

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rechteck | Das Anmerkungsrechteck, das den Standort der Anmerkung auf der Seite definiert. |
| title | Zeichenfolge | Der Titel der Anmerkung. |
| contents | Zeichenfolge | Der Inhalt der Anmerkung. |
| open | Boolesch | Ein Flag, das angibt, ob die Anmerkung zunächst geöffnet angezeigt werden soll. |
| icon | Zeichenfolge | Der Name eines Symbols, das zur Anzeige der Anmerkung verwendet wird. Dieser Wert kann sein: "Kommentar", "Schlüssel", "Notiz", "Hilfe", "NeuerAbsatz", "Absatz", "Einfügen" |
| page | Int32 | Die Nummer der ursprünglichen Seite, auf der die Textanmerkung erstellt wird. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)