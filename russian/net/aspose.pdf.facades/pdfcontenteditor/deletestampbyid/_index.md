---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Удаляет штамп на указанной странице по ID штампа
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
| pageNumber | Int32 | Номер страницы, на которой будет удален штамп. |
| stampId | Int32 | Идентификатор штампа, который должен быть удален. |

## Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Удалить штамп по ID со всех страниц документа.

```csharp
public void DeleteStampById(int stampId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stampId | Int32 | Идентификатор штампа, который должен быть удален. |

## Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)