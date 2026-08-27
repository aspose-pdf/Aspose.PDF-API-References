---
title: "FormEditor.RemoveFieldAction"
second_title: "Справочник API Aspose.PDF для .NET"
description: "метод FormEditor. Удалить действие отправки поля"
type: docs
weight: 220
url: /ru/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction method

Удалить действие отправки у поля.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | String | Имя поля. |

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


