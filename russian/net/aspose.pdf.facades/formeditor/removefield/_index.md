---
title: RemoveField
second_title: Aspose.PDF для справочника API .NET
description: Удалить поле из формы.
type: docs
weight: 250
url: /ru/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Удалить поле из формы.

```csharp
public void RemoveField(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля, которое необходимо удалить. |

### Примеры

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Смотрите также

* class [FormEditor](../../formeditor)
* пространство имен [Aspose.Pdf.Facades](../../formeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
