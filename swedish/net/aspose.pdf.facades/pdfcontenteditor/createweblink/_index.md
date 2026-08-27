---
title: "PdfContentEditor.CreateWebLink"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor‑metod. Skapar en webblänk i PDF‑dokument"
type: docs
weight: 300
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

Skapar en webblänk i PDF-dokument.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| url | String | Webblänkens destination. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln som är bunden till webblänken kommer att skapas. |
| clr | Color | Färgen på rektangeln för aktivt klick. |
| actionName | Enum[] | Arrayen med åtgärder (medlemmar av PredefinedAction‑enum) som motsvarar körning av menyalternativ i Acrobat‑visaren. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

Skapar en webblänk i PDF-dokument.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| url | String | Webblänkens destination. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln bunden till webblänken kommer att skapas. |
| clr | Color | Färgen på rektangeln för aktivt klick. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

Skapar en webblänk i PDF-dokument.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för aktivt klick. |
| url | String | Webblänkens destination. |
| originalPage | Int32 | Numret på den ursprungliga sidan där rektangeln bunden till webblänken kommer att skapas. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


