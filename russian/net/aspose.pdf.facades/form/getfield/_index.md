---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Метод Form. Получает значение поля в соответствии с его именем поля
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/form/getfield/
---
## Метод Form.GetField

Получает значение поля в соответствии с его именем поля.

```csharp
public string GetField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля. |

### Возвращаемое значение

Значение поля.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)