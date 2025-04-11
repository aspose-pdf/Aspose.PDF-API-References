---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Skapar en länk till JavaScript i PDF-dokument
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink metod

Skapar en länk till JavaScript i PDF-dokument.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| code | Sträng | JavaScript-koden. |
| rect | Rektangel | Rektangeln för aktiv klick. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln kopplas till länken kommer att skapas. |
| color | Färg | Färgen på rektangeln för aktiv klick. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)