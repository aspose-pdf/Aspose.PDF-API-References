---
title: "PdfContentEditor.CreateLocalLink"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Skapar en lokal länk i PDF-dokumentet"
type: docs
weight: 190
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

Skapar en lokal länk i PDF-dokument.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| desPage | Int32 | Destinationssidan. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till den lokala länken skapas. |
| clr | Color | Färgen på rektangeln för aktivt klick. |
| actionName | Enum[] | Arrayen med åtgärder (medlemmar av PredefinedAction‑enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

Skapar en lokal länk i PDF-dokument.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| desPage | Int32 | Destinationssidan. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till den lokala länken skapas. |
| clr | Color | Färgen på rektangeln för aktivt klick. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

Skapar en lokal länk i PDF-dokument.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| desPage | Int32 | Destinationssidan. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till den lokala länken skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


