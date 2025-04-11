---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Метод Form. Возвращает тип поля
type: docs
weight: 240
url: /ru/net/aspose.pdf.facades/form/getfieldtype/
---
## Метод Form.GetFieldType

Возвращает тип поля.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля. |

### Возвращаемое значение

Элемент перечисления FileType, соответствующий типу поля.

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### См. также

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)