---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Popup-Annotation im PDF-Dokument
type: docs
weight: 250
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup-Methode

Erstellt eine Popup-Annotation im PDF-Dokument.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rechteck | Das Annotationsrechteck, das den Standort der Annotation auf der Seite definiert. |
| contents | Zeichenfolge | Der Inhalt der Annotation. |
| open | Boolean | Ein Flag, das angibt, ob die Popup-Annotation anfänglich geöffnet angezeigt werden soll. |
| page | Int32 | Die Nummer der Originalseite, auf der die Annotation erstellt wird. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)