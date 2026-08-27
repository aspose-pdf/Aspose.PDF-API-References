---
title: "Form.GetButtonOptionCurrentValue"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Возвращает текущее значение для полей вариантов радиокнопок"
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

Возвращает текущее значение для полей вариантов радиокнопок.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля |

### Возвращаемое значение

Строковое значение текущей группы радиокнопок. См. также [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


