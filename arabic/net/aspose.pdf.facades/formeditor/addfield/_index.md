---
title: "FormEditor.AddField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. إضافة حقل من النوع المحدد إلى النموذج"
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

إضافة حقل من النوع المحدد إلى النموذج.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldType | FieldType | نوع الحقل الذي يجب إضافته. |
| fieldName | String | اسم الحقل الذي يجب إضافته. |
| pageNum | Int32 | رقم الصفحة حيث يجب وضع الحقل الجديد. |
| llx | Single | الإحداثي السيني للزاوية السفلية اليسرى للحقل. |
| lly | Single | الإحداثي الرأسي للزاوية السفلية اليسرى للحقل. |
| urx | Single | الإحداثي السيني للزاوية العلوية اليمنى للحقل. |
| ury | Single | الإحداثي الصادي للزاوية العلوية اليمنى للحقل. |

### قيمة الإرجاع

صحيح إذا تم إضافة الحقل بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### انظر أيضًا

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

إضافة حقل من النوع المحدد إلى النموذج.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldType | FieldType | نوع الحقل الذي يجب إضافته. |
| fieldName | String | اسم الحقل الذي يجب إضافته. |
| initValue | String | القيمة الأولية للحقل. |
| pageNum | Int32 | رقم الصفحة حيث يجب وضع الحقل الجديد. |
| llx | Single | الإحداثي السيني للزاوية السفلية اليسرى للحقل. |
| lly | Single | الإحداثي الرأسي للزاوية السفلية اليسرى للحقل. |
| urx | Single | الإحداثي السيني للزاوية العلوية اليمنى للحقل. |
| ury | Single | الإحداثي الصادي للزاوية العلوية اليمنى للحقل. |

### قيمة الإرجاع

صحيح إذا تم إضافة الحقل بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### انظر أيضًا

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


