---
title: CreateFileAttachment
second_title: Aspose.PDF för .NET API Referens
description: Skapar anteckning för filbilaga.
type: docs
weight: 150
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Skapar anteckning för filbilaga.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Anteckningsrektangeln som definierar platsen för anteckningen på sidan. |
| contents | String | Innehållet i anteckningen. |
| filePath | String | Sökvägen till filen bifogas. |
| page | Int32 | Antalet originalsida där anteckningen kommer att skapas. |
| name | String | Namnet på en ikon kommer att användas för att visa annoteringen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |

### Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Skapar anteckning för filbilaga.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Anteckningsrektangeln som definierar platsen för anteckningen på sidan. |
| contents | String | Innehållet i anteckningen. |
| filePath | String | Sökvägen till filen bifogas. |
| page | Int32 | Antalet originalsida där anteckningen kommer att skapas. |
| name | String | Namnet på en ikon kommer att användas för att visa annoteringen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Ikonens opacitet från 0 till 1: 0 - helt transparent, 1 - helt ogenomskinlig. |

### Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Skapar anteckning för filbilaga.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Anteckningsrektangeln som definierar platsen för anteckningen på sidan. |
| contents | String | Innehållet i anteckningen. |
| attachmentStream | Stream | Den bifogade filströmmen. |
| attachmentName | String | Bilagans namn. |
| page | Int32 | Antalet originalsida där anteckningen kommer att skapas. |
| name | String | Namnet på en ikon kommer att användas för att visa annoteringen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |

### Exempel

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

* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Skapar anteckning för filbilaga.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | Anteckningsrektangeln som definierar platsen för anteckningen på sidan. |
| contents | String | Innehållet i anteckningen. |
| attachmentStream | Stream | Den bifogade filströmmen. |
| attachmentName | String | Bilagans namn. |
| page | Int32 | Antalet originalsida där anteckningen kommer att skapas. |
| name | String | Namnet på en ikon kommer att användas för att visa annoteringen. Detta värde kan vara: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Ikonens opacitet från 0 till 1: 0 - helt transparent, 1 - helt ogenomskinlig. |

### Exempel

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

* class [PdfContentEditor](../../pdfcontenteditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfcontenteditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
