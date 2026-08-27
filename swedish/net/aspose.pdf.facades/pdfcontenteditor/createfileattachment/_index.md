---
title: "PdfContentEditor.CreateFileAttachment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor-metod. Skapar filbilaggsannotation"
type: docs
weight: 150
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Skapar filbilageannotation.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| innehåll | String | Innehållet i annotationen. |
| filePath | String | Sökvägen till filen kommer att bifogas. |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| namn | String | Namnet på en ikon kommer att användas vid visning av annotationen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Skapar filbilageannotation.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| innehåll | String | Innehållet i annotationen. |
| filePath | String | Sökvägen till filen kommer att bifogas. |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| namn | String | Namnet på en ikon kommer att användas vid visning av annotationen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Ikonens opacitet från 0 till 1: 0 - helt transparent, 1 - helt ogenomskinlig. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Skapar filbilageannotation.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| innehåll | String | Innehållet i annotationen. |
| attachmentStream | Stream | Bilagans filström |
| attachmentName | String | Bilagans namn |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| namn | String | Namnet på en ikon kommer att användas vid visning av annotationen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Skapar filbilageannotation.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Rektangeln för annotationen som definierar placeringen av annotationen på sidan. |
| innehåll | String | Innehållet i annotationen. |
| attachmentStream | Stream | Bilagans filström |
| attachmentName | String | Bilagans namn |
| sida | Int32 | Numret på den ursprungliga sidan där annotationen kommer att skapas. |
| namn | String | Namnet på en ikon kommer att användas vid visning av annotationen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Ikonens opacitet från 0 till 1: 0 - helt transparent, 1 - helt ogenomskinlig. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


