---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Skapar markup-anteckning i PDF-dokument
type: docs
weight: 200
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup metod

Skapar markup-anteckning i PDF-dokument.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln som definierar platsen för anteckningen på sidan. |
| contents | String | Innehållet i anteckningen. |
| type | Int32 | Typen av markup-anteckning. Kan vara 0 (Markera), 1 (Understrykning), 2 (Genomstrykning), 3 (Vågig). |
| page | Int32 | Numret på den ursprungliga sidan där anteckningen kommer att skapas. |
| clr | Color | Färgen på markup. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)