---
title: "PdfContentEditor.CreatePopup"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Skapar popup-anteckning i PDF-dokument"
type: docs
weight: 250
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

Skapar popup-annotation i PDF-dokument.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| innehåll | String | Innehållet i annotationen. |
| öppen | Boolean | En flagga som anger om popup-anteckningen initialt ska visas öppen. |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


