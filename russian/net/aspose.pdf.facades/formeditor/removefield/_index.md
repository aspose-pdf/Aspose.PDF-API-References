---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Удалить поле из формы
type: docs
weight: 210
url: /ru/net/aspose.pdf.facades/formeditor/removefield/
---
## Метод FormEditor.RemoveField

Удалить поле из формы.

```csharp
public void RemoveField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое должно быть удалено. |

## Примеры

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)