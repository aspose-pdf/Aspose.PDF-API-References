---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Устанавливает максимальное количество символов в текстовом поле
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## Метод FormEditor.SetFieldLimit

Устанавливает максимальное количество символов в текстовом поле.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя текстового поля. |
| fieldLimit | Int32 | Новое значение лимита для поля. |

### Возвращаемое значение

true, если лимит поля был успешно установлен.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)