---
title: SetFieldLimit
second_title: Aspose.PDF для справочника API .NET
description: Устанавливает максимальное количество символов в текстовом поле.
type: docs
weight: 350
url: /ru/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

Устанавливает максимальное количество символов в текстовом поле.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя текстового поля. |
| fieldLimit | Int32 | Новое значение лимита для поля. |

### Возвращаемое значение

true, если ограничение поля было успешно установлено.

### Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Смотрите также

* class [FormEditor](../../formeditor)
* пространство имен [Aspose.Pdf.Facades](../../formeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->