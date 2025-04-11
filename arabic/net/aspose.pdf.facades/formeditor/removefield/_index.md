---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. إزالة حقل من النموذج
type: docs
weight: 210
url: /ar/net/aspose.pdf.facades/formeditor/removefield/
---
## طريقة FormEditor.RemoveField

إزالة حقل من النموذج.

```csharp
public void RemoveField(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل الذي يجب إزالته. |

## أمثلة

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)