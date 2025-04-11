---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Skapar en gummistämpelannotering
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Skapar en gummistämpelannotering.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| annotRect | Rectangle | Annoteringsrektangeln som definierar platsen för annoteringen på sidan. |
| icon | String | En ikon som ska användas för att visa annoteringen. Standardvärde: 'Draft'. |
| annotContents | String | Innehållet i annoteringen. |
| color | Color | Färgen på annoteringen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Skapar en gummistämpelannotering.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| annotRect | Rectangle | Annoteringsrektangeln som definierar platsen för annoteringen på sidan. |
| annotContents | String | Innehållet i annoteringen. |
| color | Color | Färgen på annoteringen. |
| appearanceFile | String | Sökvägen till utseendefilen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Skapar en gummistämpelannotering.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| annotRect | Rectangle | Annoteringsrektangeln som definierar platsen för annoteringen på sidan. |
| annotContents | String | Innehållet i annoteringen. |
| color | Color | Färgen på annoteringen. |
| appearanceStream | Stream | Strömmen av utseendefilen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)