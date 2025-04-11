---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Получить ограничение текстового поля
type: docs
weight: 230
url: /ru/net/aspose.pdf.facades/form/getfieldlimit/
---
## Метод Form.GetFieldLimit

Получить ограничение текстового поля.

```csharp
public int GetFieldLimit(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Квалифицированное имя поля. |

### Возвращаемое значение

Возвращает количество символов, которое может быть заполнено в текстовом поле. Если не установлено, возвращает 0.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)