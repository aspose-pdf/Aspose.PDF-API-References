---
title: "FormEditor.RemoveField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. إزالة الحقل من النموذج"
type: docs
weight: 210
url: /ar/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

أزل الحقل من النموذج.

```csharp
public void RemoveField(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي يجب إزالته. |

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


