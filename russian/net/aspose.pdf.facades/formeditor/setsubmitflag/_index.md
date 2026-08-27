---
title: "FormEditor.SetSubmitFlag"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Устанавливает флаг отправки для кнопки submit."
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

Устанавливает флаг отправки для кнопки submit.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя кнопки submit. |
| submitFormFlag | SubmitFormFlag | Флаг отправки. |

### Возвращаемое значение

true, если поле найдено и флаг отправки успешно установлен.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### См. также

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


