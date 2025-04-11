---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Метод формы. Получает поля опций радиокнопок и связанные значения на основе имени поля. Этот метод имеет значение для групп радиокнопок
type: docs
weight: 190
url: /ru/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Метод Form.GetButtonOptionValues

Получает поля опций радиокнопок и связанные значения на основе имени поля. Этот метод имеет значение для групп радиокнопок.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля |

### Возвращаемое значение

Хэш-таблица значений опций, индексированная по имени элемента формы

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)