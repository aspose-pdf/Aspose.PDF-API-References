---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfPageEditor. Возвращает размер указанного бокса в документе"
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

Возвращает размер указанного блока в Document.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Int32 | Индекс страницы. Страницы документа нумеруются с 1. |
| pageBoxName | String | Имя типа бокса. Допустимые значения: "art", "bleed", "crop", "media", "trim". |

### Возвращаемое значение

Прямоугольник, содержащий запрошенный бокс.

## Примеры

Следующий пример демонстрирует, как получить media box первой страницы:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### См. также

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


