---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Изменить имя поля
type: docs
weight: 230
url: /ru/net/aspose.pdf.facades/formeditor/renamefield/
---
## Метод FormEditor.RenameField

Изменить имя поля.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Старое имя поля. |
| newFieldName | String | Новое имя поля. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)