---
title: "Form.GetField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Получает значение поля согласно его имени."
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

Получает значение поля по его имени.

```csharp
public string GetField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полностью квалифицированное имя поля. |

### Возвращаемое значение

Значение поля.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


