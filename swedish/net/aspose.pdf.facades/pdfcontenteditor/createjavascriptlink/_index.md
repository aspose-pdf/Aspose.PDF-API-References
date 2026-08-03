---
title: "PdfContentEditor.CreateJavaScriptLink"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor-metod. Skapar en länk till JavaScript i PDF-dokument."
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

Skapar en länk till JavaScript i PDF-dokument.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kod | String | JavaScript-koden. |
| rect | Rectangle | Rektangeln för aktivt klick. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| color | Color | Färgen på rektangeln för aktivt klick. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


