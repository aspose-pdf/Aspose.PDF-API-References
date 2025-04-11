---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Skapar textkommentar i PDF-dokument
type: docs
weight: 290
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText metod

Skapar textkommentar i PDF-dokument

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Den annoteringsrektangel som definierar platsen för annoteringen på sidan. |
| title | String | Titeln på annoteringen. |
| contents | String | Innehållet i annoteringen. |
| open | Boolean | En flagga som specificerar om annoteringen initialt ska visas öppen. |
| icon | String | Namnet på en ikon som kommer att användas för att visa annoteringen. Detta värde kan vara: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| page | Int32 | Numret på den ursprungliga sidan där textkommentaren kommer att skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)