---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt Linienannotation
type: docs
weight: 180
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine-Methode

Erstellt Linienannotation.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rechteck | Das Annotationsrechteck, das den Standort der Annotation auf der Seite definiert. |
| contents | Zeichenfolge | Der Inhalt der Annotation. |
| x1 | Einzel | Die startende horizontale Koordinate der Linie. |
| y1 | Einzel | Die startende vertikale Koordinate der Linie. |
| x2 | Einzel | Die endende horizontale Koordinate der Linie. |
| y2 | Einzel | Die endende vertikale Koordinate der Linie. |
| page | Int32 | Die Nummer der Originalseite, auf der die Annotation erstellt wird. |
| border | Int32 | Die Randbreite in Punkten. Wenn dieser Wert 0 ist, wird kein Rand gezeichnet. Standardwert ist 1. |
| clr | Farbe | Die Farbe der Linie. |
| borderStyle | Zeichenfolge | Der Randstil, der die Breite und das Strichmuster angibt, das beim Zeichnen der Linie verwendet werden soll. Dieser Wert kann sein: "S" (Durchgehend), "D" (Gestrichelt), "B" (Abgerundet), "I" (Eingefügt), "U" (Unterstrichen). |
| dashArray | Int32[] | Ein Strichmuster, das ein Muster von Strichen und Lücken definiert, das beim Zeichnen eines gestrichelten Randes verwendet werden soll. Wenn es verwendet wird, muss borderStyle entsprechend auf "D" gesetzt werden. |
| LEArray | Zeichenfolge[] | Ein Array von zwei Werten, die jeweils den Anfangs- und Endstil der zeichnenden Linie angeben. Die Werte können sein: "Quadrat", "Kreis", "Raute", "OffenerPfeil", "GeschlossenerPfeil", "Keine", "Stumpf", "ROffenerPfeil", "RGeschlossenerPfeil", "Schräg". |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)