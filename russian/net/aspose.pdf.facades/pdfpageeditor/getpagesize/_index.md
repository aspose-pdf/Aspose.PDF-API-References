---
title: GetPageSize
second_title: Aspose.PDF для справочника API .NET
description: Возвращает размер указанной страницы.
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

Возвращает размер указанной страницы.

```csharp
public PageSize GetPageSize(int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Индекс страницы. Страницы документа нумеруются с 1. |

### Возвращаемое значение

Результатом является экземпляр PageSize. Используйте свойства Width и Height возвращаемого объекта, чтобы получить ширину и высоту страницы.

### Примеры

В следующем примере демонстрируется использование метода GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Смотрите также

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfPageEditor](../../pdfpageeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfpageeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->