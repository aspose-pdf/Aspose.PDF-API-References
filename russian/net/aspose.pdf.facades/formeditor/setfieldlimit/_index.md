---
title: "FormEditor.SetFieldLimit"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Устанавливает максимальное количество символов в текстовом поле"
type: docs
weight: 310
url: /ru/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

Устанавливает максимальное количество символов текстового поля.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя текстового поля. |
| fieldLimit | Int32 | Новое значение ограничения для поля. |

### Возвращаемое значение

true, если ограничение поля успешно установлено.

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


