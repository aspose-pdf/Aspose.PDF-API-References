---
title: "PdfContentEditor.CreateApplicationLink"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor-metod. Skapar en länk för att starta ett program i PDF-dokument"
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Skapar en länk för att starta ett program i PDF-dokument.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| program | String | Sökvägen till programmet som ska startas. |
| sida | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| clr | Color | Färgen på rektangeln för aktivt klick. |
| actionName | Enum[] | Arrayen med åtgärder (medlemmar av PredefinedAction‑enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Skapar en länk för att starta ett program i PDF-dokument.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| program | String | Sökvägen till programmet som ska startas. |
| sida | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |
| clr | Color | Färgen på rektangeln för aktivt klick. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Skapar en länk för att starta ett program i PDF-dokument.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| program | String | Sökvägen till programmet som ska startas. |
| sida | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till länken kommer att skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


