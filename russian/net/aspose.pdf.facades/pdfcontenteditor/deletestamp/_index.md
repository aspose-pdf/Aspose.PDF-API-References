---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Удаляет несколько штампов на указанной странице по индексам штампов
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## Метод PdfContentEditor.DeleteStamp

Удаляет несколько штампов на указанной странице по индексам штампов.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы, на которой будет удален штамп. |
| index | Int32[] | Индексы штампов. |

## Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)