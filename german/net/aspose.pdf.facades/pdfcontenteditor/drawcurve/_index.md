---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Kurvenannotation
type: docs
weight: 360
url: /de/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve-Methode

Erstellt eine Kurvenannotation.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lineInfo | LineInfo | Die Instanz der LineInfo-Klasse. |
| page | Int32 | Die Nummer der Originalseite, auf der die Annotation erstellt wird. |
| annotRect | Rectangle | Das Annotationsrechteck, das den Standort der Annotation auf der Seite definiert. |
| annotContents | String | Der Inhalt der Annotation. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [LineInfo](../../lineinfo/)
* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)