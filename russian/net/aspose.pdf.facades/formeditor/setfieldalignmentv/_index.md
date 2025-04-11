---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Установить стиль вертикального выравнивания текстового поля
type: docs
weight: 270
url: /ru/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## Метод FormEditor.SetFieldAlignmentV

Установить стиль вертикального выравнивания текстового поля.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Квалифицированное имя поля. |
| alignment | Int32 | Определение стиля выравнивания, включая FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle и FormFieldFacade.AlignRight. |

### Возвращаемое значение

true, если поле было найдено и выравнивание было успешно установлено.

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)