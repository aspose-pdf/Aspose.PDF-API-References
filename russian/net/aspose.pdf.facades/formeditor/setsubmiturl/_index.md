---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Устанавливает URL кнопки
type: docs
weight: 340
url: /ru/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## Метод FormEditor.SetSubmitUrl

Устанавливает URL кнопки.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя кнопки отправки. |
| url | String | Полностью квалифицированный URL. |

### Возвращаемое значение

true, если URL для кнопки был успешно установлен.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)