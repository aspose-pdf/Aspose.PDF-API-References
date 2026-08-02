---
title: "Form.GetFieldFacade"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Form. Возвращает объект FrofmFieldFacade, содержащий все атрибуты внешнего вида"
type: docs
weight: 210
url: /ru/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

Возвращает объект FrofmFieldFacade, содержащий все атрибуты внешнего вида.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля для чтения. |

### Возвращаемое значение

Объект FormFieldFacade

### См. также

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


