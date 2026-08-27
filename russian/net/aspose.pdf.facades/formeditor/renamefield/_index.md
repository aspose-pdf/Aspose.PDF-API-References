---
title: "FormEditor.RenameField"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FormEditor. Изменяет имя поля"
type: docs
weight: 230
url: /ru/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


