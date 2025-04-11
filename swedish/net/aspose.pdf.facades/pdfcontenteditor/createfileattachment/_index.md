---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Skapar filbilaga annotation
type: docs
weight: 150
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Skapar filbilaga annotation.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Den annoteringsrektangel som definierar platsen för annoteringen på sidan. |
| contents | String | Innehållet i annoteringen. |
| filePath | String | Sökvägen till filen som kommer att bifogas. |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| name | String | Namnet på en ikon som kommer att användas för att visa annoteringen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Skapar filbilaga annotation.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Den annoteringsrektangel som definierar platsen för annoteringen på sidan. |
| contents | String | Innehållet i annoteringen. |
| filePath | String | Sökvägen till filen som kommer att bifogas. |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| name | String | Namnet på en ikon som kommer att användas för att visa annoteringen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Ikonens opacitet från 0 till 1: 0 - helt transparent, 1 - helt ogenomskinlig. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Skapar filbilaga annotation.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Den annoteringsrektangel som definierar platsen för annoteringen på sidan. |
| contents | String | Innehållet i annoteringen. |
| attachmentStream | Stream | Bilagefilströmmen. |
| attachmentName | String | Bilagans namn. |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| name | String | Namnet på en ikon som kommer att användas för att visa annoteringen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |

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

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Skapar filbilaga annotation.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Den annoteringsrektangel som definierar platsen för annoteringen på sidan. |
| contents | String | Innehållet i annoteringen. |
| attachmentStream | Stream | Bilagefilströmmen. |
| attachmentName | String | Bilagans namn. |
| page | Int32 | Numret på den ursprungliga sidan där annoteringen kommer att skapas. |
| name | String | Namnet på en ikon som kommer att användas för att visa annoteringen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |
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

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)