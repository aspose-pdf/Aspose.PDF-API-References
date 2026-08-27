---
title: "FormEditor.SetSubmitUrl"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Устанавливает URL кнопки"
type: docs
weight: 340
url: /ru/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Устанавливает URL кнопки.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя кнопки отправки. |
| url | String | Полный URL. |

### Возвращаемое значение

true, если URL для кнопки был успешно установлен.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


