---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Skapar fri textkommentar i PDF-dokument
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText metod

Skapar fri textkommentar i PDF-dokument

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Den annoteringsrektangel som definierar platsen för annoteringen på sidan. |
| contents | String | Innehållet i annoteringen. |
| page | Int32 | Numret på den ursprungliga sidan där textannoteringen kommer att skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)