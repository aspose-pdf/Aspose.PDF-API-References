---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Установить флаг отправки кнопки отправки
type: docs
weight: 330
url: /ru/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## Метод FormEditor.SetSubmitFlag

Установить флаг отправки кнопки отправки.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя кнопки отправки. |
| submitFormFlag | SubmitFormFlag | Флаг отправки. |

### Возвращаемое значение

true, если поле было найдено и флаг отправки был успешно установлен.

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