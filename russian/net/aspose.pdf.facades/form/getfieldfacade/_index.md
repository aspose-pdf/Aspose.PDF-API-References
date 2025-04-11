---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Метод Form. Возвращает объект FrofmFieldFacade, содержащий все атрибуты внешнего вида
type: docs
weight: 210
url: /ru/net/aspose.pdf.facades/form/getfieldfacade/
---
## Метод Form.GetFieldFacade

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

* класс [FormFieldFacade](../../formfieldfacade/)
* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)