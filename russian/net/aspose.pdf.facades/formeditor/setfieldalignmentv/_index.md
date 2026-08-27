---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Установить стиль вертикального выравнивания текстового поля"
type: docs
weight: 270
url: /ru/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

Установить стиль вертикального выравнивания текстового поля.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Полное (квалифицированное) имя поля. |
| alignment | Int32 | Определение стиля выравнивания, включая FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle и FormFieldFacade.AlignRight. |

### Возвращаемое значение

true, если поле найдено и выравнивание успешно применено.

## Примеры

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


