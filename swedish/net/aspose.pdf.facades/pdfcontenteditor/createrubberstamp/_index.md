---
title: "PdfContentEditor.CreateRubberStamp"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor-metod. Skapar en gummistämpelannotation"
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Skapar en gummistämpel-annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| icon | String | En ikon ska användas för att visa annotationen. Standardvärde: 'Draft'. |
| annotContents | String | Innehållet i annotationen. |
| color | Color | Färgen på annotationen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Skapar en gummistämpel-annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| annotContents | String | Innehållet i annotationen. |
| color | Color | Färgen på annotationen. |
| appearanceFile | String | Sökvägen till appearance file. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Skapar en gummistämpel-annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| annotRect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| annotContents | String | Innehållet i annotationen. |
| color | Color | Färgen på annotationen. |
| appearanceStream | Stream | Strömmen för appearance file. |

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

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


