---
title: "PdfContentEditor.CreateText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Skapar textanteckning i PDF-dokument."
type: docs
weight: 290
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

Skapar textannotation i PDF-dokument

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| titel | String | Anteckningens titel. |
| innehåll | String | Innehållet i annotationen. |
| öppen | Boolean | En flagga som anger om anteckningen initialt ska visas öppen. |
| icon | String | Namnet på en ikon som kommer att användas vid visning av anteckningen. Detta värde kan vara: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| sida | Int32 | Numret på den ursprungliga sidan där textanteckningen kommer att skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


