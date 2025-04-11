---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تعيين سمات الحقل
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## طريقة FormEditor.SetFieldAttribute

تعيين سمات الحقل.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي يجب تعيين سماته. |
| flag | PropertyFlag | العلم (NoExport/ReadOnly/Required) |

### قيمة الإرجاع

true إذا تم تعيين السمة بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### انظر أيضًا

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)