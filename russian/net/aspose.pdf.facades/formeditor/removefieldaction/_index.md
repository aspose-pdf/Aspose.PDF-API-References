---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: Метод FormEditor. Удалить действие отправки поля
type: docs
weight: 220
url: /ru/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## Метод FormEditor.RemoveFieldAction

Удалить действие отправки поля.

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

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)