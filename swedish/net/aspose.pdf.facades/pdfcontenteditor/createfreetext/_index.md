---
title: "PdfContentEditor.CreateFreeText"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Skapar fri textanteckning i PDF-dokument."
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText method

Skapar fri text-annotation i PDF-dokument

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| innehåll | String | Innehållet i annotationen. |
| sida | Int32 | Numret på den ursprungliga sidan där textanteckningen kommer att skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


