---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfPageEditor. Возвращает размер страницы указанной страницы
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## Метод PdfPageEditor.GetPageSize

Возвращает размер страницы указанной страницы.

```csharp
public PageSize GetPageSize(int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Индекс страницы. Страницы документа нумеруются с 1. |

### Возвращаемое значение

Результат является экземпляром PageSize. Используйте свойства Width и Height возвращаемого объекта, чтобы получить ширину и высоту страницы.

## Примеры

Следующий пример демонстрирует использование метода GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### См. также

* класс [PageSize](../../../aspose.pdf/pagesize/)
* класс [PdfPageEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)