---
title: AddDocumentAttachment
second_title: Aspose.PDF для справочника API .NET
description: Добавляет вложение к документу без аннотации.
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Добавляет вложение к документу без аннотации.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileAttachmentPath | String | Путь к файлу будет прикреплен. |
| description | String | Информация описания. |

### Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Добавляет вложение к документу без аннотации.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileAttachmentStream | Stream | Поток файла будет прикреплен. |
| fileAttachmentName | String | Имя вложения. |
| description | String | Информация описания. |

### Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->