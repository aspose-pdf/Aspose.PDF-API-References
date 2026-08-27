---
title: "FormEditor.RemoveField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Удаляет поле из формы"
type: docs
weight: 210
url: /ru/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


