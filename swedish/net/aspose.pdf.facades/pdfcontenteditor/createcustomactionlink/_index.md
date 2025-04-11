---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Skapar en länk till anpassade åtgärder i PDF-dokument
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink metod

Skapar en länk till anpassade åtgärder i PDF-dokument.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktiv klick. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln kopplas till länken kommer att skapas. |
| color | Color | Färgen på rektangeln för aktiv klick. |
| actionName | Enum[] | Array av åtgärder (medlemmar av PredefinedAction enum) som motsvarar utförande av menyobjekt i Acrobat-visaren. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)