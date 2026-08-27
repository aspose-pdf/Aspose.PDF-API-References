---
title: "PdfContentEditor.CreateMarkup"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor‑metod. Skapar markup‑annotation i PDF‑dokumentet."
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

Skapar markup-annotation i PDF-dokument.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln som definierar annotationens placering på sidan. |
| innehåll | String | Innehållet i annotationen. |
| typ | Int32 | Typen av markup‑annotation. Kan vara 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly). |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| clr | Color | Färgen på markup. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


