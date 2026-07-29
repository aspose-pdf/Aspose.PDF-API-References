---
title: "FormEditor.SetFieldLimit"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تحدد الحد الأقصى لعدد الأحرف في حقل النص"
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

يضبط الحد الأقصى لعدد الأحرف لحقل النص.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم حقل النص. |
| fieldLimit | Int32 | القيمة الجديدة للحد في الحقل. |

### قيمة الإرجاع

صحيح إذا تم تعيين حد الحقل بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


