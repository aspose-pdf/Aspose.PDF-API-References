---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-metod. Lägger till dokumentbilaga utan anteckning
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Lägger till dokumentbilaga utan anteckning.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileAttachmentPath | Sträng | Sökvägen till filen som ska bifogas. |
| description | Sträng | Beskrivningsinformation. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Lägger till dokumentbilaga utan anteckning.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileAttachmentStream | Ström | Strömmen av filen som ska bifogas. |
| fileAttachmentName | Sträng | Bilagans namn. |
| description | Sträng | Beskrivningsinformation. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)