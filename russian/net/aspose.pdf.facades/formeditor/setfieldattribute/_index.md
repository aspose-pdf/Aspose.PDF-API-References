---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Установить атрибуты поля
type: docs
weight: 290
url: /ru/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## Метод FormEditor.SetFieldAttribute

Установить атрибуты поля.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, для которого должны быть установлены атрибуты. |
| flag | PropertyFlag | Флаг (NoExport/ReadOnly/Required) |

### Возвращаемое значение

true, если атрибут был успешно установлен.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### См. также

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)