---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfPageEditor. Возвращает размер указанного прямоугольника в документе
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## Метод PdfPageEditor.GetPageBoxSize

Возвращает размер указанного прямоугольника в документе.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Индекс страницы. Страницы документа нумеруются с 1. |
| pageBoxName | String | Название типа прямоугольника. Допустимые значения: "art", "bleed", "crop", "media", "trim". |

### Возвращаемое значение

Прямоугольник, который содержит запрашиваемый прямоугольник.

## Примеры

Следующий пример демонстрирует, как получить медиаплощадку первой страницы:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### См. также

* класс [PdfPageEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)