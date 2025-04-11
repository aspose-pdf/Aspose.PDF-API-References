---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. إزالة إجراء الإرسال للحقل
type: docs
weight: 220
url: /ar/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## طريقة FormEditor.RemoveFieldAction

إزالة إجراء الإرسال للحقل.

```csharp
public void RemoveFieldAction(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)