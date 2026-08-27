---
title: "FormEditor.MoveField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تحديد موضع جديد للحقل"
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

حدد الموقع الجديد للحقول.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي يجب نقله. |
| llx | Single | الإحداثي السيني للزاوية السفلية اليسرى للحقل. |
| lly | Single | الإحداثي الصادي للزاوية السفلية اليسرى للحقل. |
| urx | Single | الإحداثي السيني للزاوية العلوية اليمنى للحقل. |
| ury | Single | الإحداثي الصادي للزاوية العلوية اليمنى للحقل. |

### قيمة الإرجاع

صحيح إذا تم تغيير موضع الحقل بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


