---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Quadrat-Kreis-Anmerkung
type: docs
weight: 280
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle-Methode

Erstellt eine Quadrat-Kreis-Anmerkung.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Anmerkungsrechteck, das den Standort der Anmerkung auf der Seite definiert. |
| contents | String | Der Inhalt der Anmerkung. |
| clr | Color | Die Farbe des Quadrats oder Kreises. |
| square | Boolean | Wahr (Quadrat), falsch (Kreis). |
| page | Int32 | Die Nummer der ursprünglichen Seite, auf der die Anmerkung erstellt wird. |
| borderWidth | Int32 | Die Rahmenbreite des Quadrats oder Kreises. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)