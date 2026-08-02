---
title: "Form.GetFullFieldName"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Получает полное имя поля по его короткому имени."
type: docs
weight: 250
url: /ru/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

Получает полное имя поля по его короткому имени.

```csharp
public string GetFullFieldName(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полностью квалифицированное имя поля. |

### Возвращаемое значение

Полное имя поля.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### См. также

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


