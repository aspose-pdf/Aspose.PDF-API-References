---
title: "FormEditor.SetFieldAlignment"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Устанавливает стиль выравнивания текстового поля"
type: docs
weight: 260
url: /ru/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

Установить стиль выравнивания текстового поля.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное (квалифицированное) имя поля. |
| alignment | Int32 | Определение стиля выравнивания, включая FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter и FormFieldFacade.AlignRight. |

### Возвращаемое значение

true, если поле найдено и выравнивание установлено.

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


