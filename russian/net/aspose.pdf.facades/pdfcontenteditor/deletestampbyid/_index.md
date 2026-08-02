---
title: "PdfContentEditor.DeleteStampById"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Удаляет штамп на указанной странице по ID штампа."
type: docs
weight: 340
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Удаляет штамп на указанной странице по ID штампа.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы, на которой будет удалён штамп. |
| stampId | Int32 | Идентификатор stanp, который должен быть удалён. |

## Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Удалить штамп по ID со всех страниц документа.

```csharp
public void DeleteStampById(int stampId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stampId | Int32 | Идентификатор штампа, который должен быть удалён. |

## Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


