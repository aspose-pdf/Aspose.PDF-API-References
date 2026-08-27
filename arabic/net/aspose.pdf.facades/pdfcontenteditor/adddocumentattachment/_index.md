---
title: "PdfContentEditor.AddDocumentAttachment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تُضيف مرفق مستند بدون توضيح."
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

يضيف مرفق مستند بدون توضيح.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileAttachmentPath | String | سيتم إرفاق مسار الملف. |
| الوصف | String | معلومات الوصف. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

يضيف مرفق مستند بدون توضيح.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileAttachmentStream | Stream | سيتم إرفاق تدفق الملف. |
| fileAttachmentName | String | اسم المرفق. |
| الوصف | String | معلومات الوصف. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


