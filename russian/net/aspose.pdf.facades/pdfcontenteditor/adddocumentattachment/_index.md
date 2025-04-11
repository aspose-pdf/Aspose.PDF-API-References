---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Добавляет вложение документа без аннотации
type: docs
weight: 70
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Добавляет вложение документа без аннотации.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileAttachmentPath | String | Путь к файлу, который будет прикреплен. |
| description | String | Информация о описании. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Добавляет вложение документа без аннотации.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileAttachmentStream | Stream | Поток файла, который будет прикреплен. |
| fileAttachmentName | String | Имя вложения. |
| description | String | Информация о описании. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)