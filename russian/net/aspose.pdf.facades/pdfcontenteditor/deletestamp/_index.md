---
title: DeleteStamp
second_title: Aspose.PDF для справочника API .NET
description: Удаляет несколько штампов на указанной странице по индексам штампов.
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp method

Удаляет несколько штампов на указанной странице по индексам штампов.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы, на которой штамп будет удален. |
| index | Int32[] | Штамповые индексы. |

### Примеры

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->