---
title: "PdfContentEditor.AddDocumentAttachment"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfContentEditor метод. Добавляет вложение документа без аннотации"
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
| fileAttachmentPath | String | Путь к файлу будет вложен. |
| description | String | Информация описания. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Добавляет вложение документа без аннотации.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileAttachmentStream | Stream | Поток файла будет вложен. |
| fileAttachmentName | String | Имя вложения. |
| description | String | Информация описания. |

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


