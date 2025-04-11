---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Skapar popup-anteckning i PDF-dokument
type: docs
weight: 250
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup metod

Skapar popup-anteckning i PDF-dokument.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Anteckningsrektangeln som definierar platsen för anteckningen på sidan. |
| contents | String | Innehållet i anteckningen. |
| open | Boolean | En flagga som specificerar om popup-anteckningen initialt ska visas öppen. |
| page | Int32 | Numret på den ursprungliga sidan där anteckningen kommer att skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)