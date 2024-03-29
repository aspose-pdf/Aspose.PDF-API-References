---
title: SetFieldAlignment
second_title: Aspose.PDF для справочника API .NET
description: Установить стиль выравнивания текстового поля.
type: docs
weight: 300
url: /ru/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

Установить стиль выравнивания текстового поля.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное имя поля. |
| alignment | Int32 | Определение стиля выравнивания, включая FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter и FormFieldFacade.AlignRight. |

### Возвращаемое значение

true, если true, если поле найдено и задано выравнивание.

### Примеры

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Смотрите также

* class [FormEditor](../../formeditor)
* пространство имен [Aspose.Pdf.Facades](../../formeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
