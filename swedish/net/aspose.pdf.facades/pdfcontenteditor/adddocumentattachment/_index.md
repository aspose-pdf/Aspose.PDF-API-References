---
title: "PdfContentEditor.AddDocumentAttachment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor-metod. Lägger till dokumentbilaga utan annotation"
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Lägger till dokumentbilaga utan annotation.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileAttachmentPath | String | Sökvägen till filen kommer att bifogas. |
| beskrivning | String | Beskrivningsinformationen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Lägger till dokumentbilaga utan annotation.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileAttachmentStream | Stream | Strömmen av filen kommer att bifogas. |
| fileAttachmentName | String | Bilagans namn |
| beskrivning | String | Beskrivningsinformationen. |

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

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


