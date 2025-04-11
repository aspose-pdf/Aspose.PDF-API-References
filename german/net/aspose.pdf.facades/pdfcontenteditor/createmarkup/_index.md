---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Markup-Anmerkung im PDF-Dokument
type: docs
weight: 200
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup-Methode

Erstellt eine Markup-Anmerkung im PDF-Dokument.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rechteck | Das Rechteck, das den Standort der Anmerkung auf der Seite definiert. |
| contents | Zeichenfolge | Der Inhalt der Anmerkung. |
| type | Int32 | Der Typ der Markup-Anmerkung. Kann 0 (Hervorheben), 1 (Unterstreichen), 2 (Durchstreichen), 3 (Wellig) sein. |
| page | Int32 | Die Nummer der ursprünglichen Seite, auf der die Anmerkung erstellt wird. |
| clr | Farbe | Die Farbe des Markups. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)