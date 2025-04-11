---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Метод Form. Возвращает флаги поля
type: docs
weight: 220
url: /ru/net/aspose.pdf.facades/form/getfieldflag/
---
## Метод Form.GetFieldFlag

Возвращает флаги поля.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля |

### Возвращаемое значение

Флаг свойства (ReadOnly/ Required/NoExport

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### См. также

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)