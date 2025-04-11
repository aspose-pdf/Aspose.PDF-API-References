---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Notasyon olmadan belge eki ekler
type: docs
weight: 70
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Notasyon olmadan belge eki ekler.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileAttachmentPath | String | Eklenecek dosyanın yolu. |
| description | String | Açıklama bilgisi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Notasyon olmadan belge eki ekler.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileAttachmentStream | Stream | Eklenecek dosyanın akışı. |
| fileAttachmentName | String | Eki adı. |
| description | String | Açıklama bilgisi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Ayrıca Bakınız

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)