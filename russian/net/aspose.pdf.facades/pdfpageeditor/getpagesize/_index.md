---
title: "PdfPageEditor.GetPageSize"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfPageEditor. Возвращает размер указанной страницы"
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
| страница | Int32 | Индекс страницы. Страницы документа нумеруются с 1. |

### Возвращаемое значение

Результат является экземпляром PageSize. Используйте свойства Width и Height возвращённого объекта, чтобы получить ширину и высоту страницы.

## Примеры

В следующем примере демонстрируется использование метода GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### См. также

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


