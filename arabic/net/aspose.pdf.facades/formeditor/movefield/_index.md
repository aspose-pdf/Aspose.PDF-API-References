---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تعيين موضع جديد للحقل
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/formeditor/movefield/
---
## طريقة FormEditor.MoveField

تعيين موضع جديد للحقل.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي يجب نقله. |
| llx | Single | الإحداثي السيني للزاوية السفلى اليسرى من الحقل. |
| lly | Single | الإحداثي الصادي للزاوية السفلى اليسرى من الحقل. |
| urx | Single | الإحداثي السيني للزاوية العليا اليمنى من الحقل. |
| ury | Single | الإحداثي الصادي للزاوية العليا اليمنى من الحقل. |

### قيمة الإرجاع

true إذا تم تغيير موضع الحقل بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)