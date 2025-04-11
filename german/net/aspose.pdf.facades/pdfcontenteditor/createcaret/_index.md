---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Caret-Anmerkung
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret-Methode

Erstellt eine Caret-Anmerkung.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| annotRect | Rechteck | Das Anmerkungsrechteck, das den Standort der Anmerkung auf der Seite definiert. |
| caretRect | Rechteck | Die tatsächlichen Grenzen des zugrunde liegenden Carets. |
| symbol | Zeichenfolge | Ein Symbol wird mit dem Caret verknüpft. Der Wert kann sein: "P" (Absatz), "None". |
| annotContents | Zeichenfolge | Der Inhalt der Anmerkung. |
| color | Farbe | Die Farbe der Anmerkung. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)