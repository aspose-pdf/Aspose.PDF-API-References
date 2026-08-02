---
title: "Form.GetButtonOptionValues"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Получает поля вариантов радиокнопок и связанные значения на основе имени поля. Этот метод имеет смысл для групп радиокнопок."
type: docs
weight: 190
url: /ru/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

Получает поля вариантов радиокнопок и связанные значения по имени поля. Этот метод имеет смысл для групп радиокнопок.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля |

### Возвращаемое значение

Хеш-таблица значений вариантов, ключом которой является имя элемента формы.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


