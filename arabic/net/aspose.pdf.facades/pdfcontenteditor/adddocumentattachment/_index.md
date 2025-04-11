---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تضيف مرفق مستند بدون تعليق
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

تضيف مرفق مستند بدون تعليق.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileAttachmentPath | String | مسار الملف الذي سيتم إرفاقه. |
| description | String | معلومات الوصف. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

تضيف مرفق مستند بدون تعليق.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileAttachmentStream | Stream | تدفق الملف الذي سيتم إرفاقه. |
| fileAttachmentName | String | اسم المرفق. |
| description | String | معلومات الوصف. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)