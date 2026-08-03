---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor‑metod. Skapar en länk till anpassade åtgärder i PDF‑dokumentet."
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

Skapar en länk till anpassade åtgärder i PDF-dokument.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| color | Color | Färgen på rektangeln för aktivt klick. |
| actionName | Enum[] | Arrayen med åtgärder (medlemmar av PredefinedAction‑enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


