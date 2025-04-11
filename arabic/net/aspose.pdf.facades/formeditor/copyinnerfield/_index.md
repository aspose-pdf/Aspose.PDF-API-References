---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تنسخ حقلًا موجودًا إلى نفس الموضع في رقم الصفحة المحدد. سيتم إنتاج مستند جديد يحتوي على كل ما يحتويه المستند المصدر باستثناء الحقل المنسوخ حديثًا
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

تنسخ حقلًا موجودًا إلى نفس الموضع في رقم الصفحة المحدد. سيتم إنتاج مستند جديد يحتوي على كل ما يحتويه المستند المصدر باستثناء الحقل المنسوخ حديثًا.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل القديم المؤهل بالكامل. |
| newFieldName | String | اسم الحقل الجديد المؤهل بالكامل. إذا كان null، سيتم تعيينه كـ fieldName + "~". |
| pageNum | Int32 | رقم الصفحة التي ستحتوي على الحقل الجديد. إذا كان -1، سيتم نسخ الحقل الجديد إلى نفس الصفحة التي يستضيفها القديم. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

تنسخ حقلًا موجودًا إلى موضع جديد محدد بواسطة كل من رقم الصفحة والإحداثيات. سيتم إنتاج مستند جديد يحتوي على كل ما يحتويه المستند المصدر باستثناء الحقل المنسوخ حديثًا.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | اسم الحقل القديم المؤهل بالكامل. |
| newFieldName | String | اسم الحقل الجديد المؤهل بالكامل. إذا كان null، سيتم تعيينه كـ fieldName + "~". |
| pageNum | Int32 | رقم الصفحة التي ستحتوي على الحقل الجديد. إذا كان -1، سيتم نسخ الحقل الجديد إلى نفس الصفحة التي يستضيفها القديم. |
| abscissa | Single | الإحداثي السيني للحقل الجديد. إذا كان -1، سيكون الإحداثي السيني مساوياً للأصلي. |
| ordinate | Single | الإحداثي الصادي للحقل الجديد. إذا كان -1، سيكون الإحداثي الصادي مساوياً للأصلي. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)