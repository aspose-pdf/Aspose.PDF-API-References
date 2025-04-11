---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Установите стиль выравнивания текстового поля
type: docs
weight: 260
url: /ru/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## Метод FormEditor.SetFieldAlignment

Установите стиль выравнивания текстового поля.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Квалифицированное имя поля. |
| alignment | Int32 | Определение стиля выравнивания, включая FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter и FormFieldFacade.AlignRight. |

### Возвращаемое значение

true, если поле было найдено и выравнивание было установлено.

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)