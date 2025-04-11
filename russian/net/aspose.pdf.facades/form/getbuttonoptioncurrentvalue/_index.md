---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Возвращает текущее значение для полей опций радиокнопок
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Метод Form.GetButtonOptionCurrentValue

Возвращает текущее значение для полей опций радиокнопок.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля |

### Возвращаемое значение

Строковое значение для текущей группы радиокнопок. См. также [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)