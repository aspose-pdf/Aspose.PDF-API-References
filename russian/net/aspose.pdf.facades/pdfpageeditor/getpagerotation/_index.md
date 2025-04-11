---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfPageEditor. Возвращает поворот указанной страницы
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## Метод PdfPageEditor.GetPageRotation

Возвращает поворот указанной страницы.

```csharp
public int GetPageRotation(int page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Индекс страницы. Страницы документа нумеруются с 1. |

### Возвращаемое значение

Поворот страницы в градусах.

## Примеры

Следующий пример демонстрирует, как получить поворот страницы:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### См. также

* класс [PdfPageEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)