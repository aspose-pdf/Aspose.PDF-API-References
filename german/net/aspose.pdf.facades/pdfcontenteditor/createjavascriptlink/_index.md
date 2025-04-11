---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt einen Link zu JavaScript im PDF-Dokument
type: docs
weight: 170
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink-Methode

Erstellt einen Link zu JavaScript im PDF-Dokument.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| code | String | Der JavaScript-Code. |
| rect | Rectangle | Das Rechteck für den aktiven Klick. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der das Rechteck mit dem Link erstellt wird. |
| color | Color | Die Farbe des Rechtecks für den aktiven Klick. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)