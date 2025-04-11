---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. إضافة حقل من النوع المحدد إلى النموذج
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

| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | نوع الحقل الذي يجب إضافته. |
| fieldName | String | اسم الحقل الذي يجب إضافته. |
| pageNum | Int32 | رقم الصفحة التي يجب وضع الحقل الجديد فيها. |
| llx | Single | الإحداثي السيني للزاوية السفلى اليسرى من الحقل. |
| lly | Single | الإحداثي الصادي للزاوية السفلى اليسرى من الحقل. |
| urx | Single | الإحداثي السيني للزاوية العليا اليمنى من الحقل. |
| ury | Single | الإحداثي الصادي للزاوية العليا اليمنى من الحقل. |

### Return Value

true إذا تم إضافة الحقل بنجاح.

## Examples

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | نوع الحقل الذي يجب إضافته. |
| fieldName | String | اسم الحقل الذي يجب إضافته. |
| initValue | String | القيمة الأولية للحقل. |
| pageNum | Int32 | رقم الصفحة التي يجب وضع الحقل الجديد فيها. |
| llx | Single | الإحداثي السيني للزاوية السفلى اليسرى من الحقل. |
| lly | Single | الإحداثي الصادي للزاوية السفلى اليسرى من الحقل. |
| urx | Single | الإحداثي السيني للزاوية العليا اليمنى من الحقل. |
| ury | Single | الإحداثي الصادي للزاوية العليا اليمنى من الحقل. |

### Return Value

true إذا تم إضافة الحقل بنجاح.

## Examples

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### See Also

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)