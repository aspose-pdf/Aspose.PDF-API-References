---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تعيين الحد الأقصى لعدد الأحرف في حقل النص
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## طريقة FormEditor.SetFieldLimit

تعيين الحد الأقصى لعدد الأحرف في حقل النص.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم حقل النص. |
| fieldLimit | Int32 | القيمة الجديدة للحد للحقل. |

### قيمة الإرجاع

true إذا تم تعيين حد الحقل بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)