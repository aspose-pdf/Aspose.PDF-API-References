---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Freitextanmerkung im PDF-Dokument
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText-Methode

Erstellt eine Freitextanmerkung im PDF-Dokument

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rechteck | Das Anmerkungsrechteck, das den Standort der Anmerkung auf der Seite definiert. |
| contents | Zeichenfolge | Der Inhalt der Anmerkung. |
| page | Int32 | Die Nummer der Originalseite, auf der die Textanmerkung erstellt wird. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)