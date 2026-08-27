---
title: "`PdfContentEditor.CreatePdfDocumentLink`"
second_title: "Aspose.PDF för .NET API‑referens"
description: "`PdfContentEditor`-metod. Skapar en länk till en annan PDF-dokumentsida"
type: docs
weight: 220
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## CreatePdfDocumentLink(Rectangle, string, int, int, Color, Enum[]) {#createpdfdocumentlink_2}

Skapar en länk till en annan PDF-dokumentsida.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| remotePdf | String | PDF-dokumentet vars sida kommer att öppnas. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| destinationPage | Int32 | Destinationssidan. |
| clr | Color | Färgen på rektangeln för aktivt klick. |
| actionName | Enum[] | Arrayen med åtgärder (medlemmar av PredefinedAction‑enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

Skapar en länk till en annan PDF-dokumentsida.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| remotePdf | String | PDF-dokumentet vars sida kommer att öppnas. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| destinationPage | Int32 | Destinationssidan. |
| clr | Color | Färgen på rektangeln för aktivt klick. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

Skapar en länk till en annan PDF-dokumentsida.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| remotePdf | String | PDF-dokumentet vars sida kommer att öppnas. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| destinationPage | Int32 | Destinationssidan. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


