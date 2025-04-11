---
title: PdfContentEditor.DeleteStampByIds
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Удаляет штампы с указанными идентификаторами со всех страниц документа
type: docs
weight: 350
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Удаляет штампы с указанными идентификаторами со всех страниц документа.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stampIds | Int32[] | Массив идентификаторов штампов. |

## Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Удаляет штампы на указанной странице по нескольким идентификаторам штампов.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы, на которой будут удалены штампы. |
| stampIds | Int32[] | Массив идентификаторов штампов. |

## Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)