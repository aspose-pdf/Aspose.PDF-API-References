---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Метод Form. Получает полное имя поля в соответствии с его коротким именем поля
type: docs
weight: 250
url: /ru/net/aspose.pdf.facades/form/getfullfieldname/
---
## Метод Form.GetFullFieldName

Получает полное имя поля в соответствии с его коротким именем поля.

```csharp
public string GetFullFieldName(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное квалифицированное имя поля. |

### Возвращаемое значение

Полное имя поля.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)