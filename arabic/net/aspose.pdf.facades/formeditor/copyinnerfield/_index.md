---
title: "FormEditor.CopyInnerField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تنسخ حقلًا موجودًا إلى نفس الموقع في رقم الصفحة المحدد. سيتم إنشاء مستند جديد يحتوي على كل ما في المستند الأصلي باستثناء الحقل المنسوخ حديثًا."
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

ينسخ حقلًا موجودًا إلى نفس الموقع في رقم الصفحة المحدد. سيتم إنشاء مستند جديد يحتوي على كل ما يحتويه المستند الأصلي باستثناء الحقل المنسوخ حديثًا.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل القديم. |
| newFieldName | String | اسم الحقل المؤهل بالكامل الجديد. إذا كان null، سيتم تعيينه كـ fieldName + "~". |
| pageNum | Int32 | عدد الصفحة التي ستحمل الحقل الجديد. إذا كان -1، سيتم نسخ الحقل الجديد إلى نفس الصفحة التي يستضيفها القديم. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//ينشئ نسخة من حقل النص في الصفحة الثانية.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

ينسخ حقلًا موجودًا إلى موقع جديد يتم تحديده برقم الصفحة والإحداثيات. سيتم إنشاء مستند جديد يحتوي على كل ما يحتويه المستند الأصلي باستثناء الحقل المنسوخ حديثًا.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل القديم. |
| newFieldName | String | اسم الحقل المؤهل بالكامل الجديد. إذا كان null، سيتم تعيينه كـ fieldName + "~". |
| pageNum | Int32 | عدد الصفحة التي ستحمل الحقل الجديد. إذا كان -1، سيتم نسخ الحقل الجديد إلى نفس الصفحة التي يستضيفها القديم. |
| الإحداثي السيني | Single | الإحداثي السيني للحقل الجديد. إذا كان -1، سيُساوي الإحداثي السيني الأصلي. |
| الإحداثي الصادي | Single | الإحداثي الصادي للحقل الجديد. إذا كان -1، سيُساوي الإحداثي الصادي الأصلي. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//ينشئ نسخة من حقل النص في الصفحة الثانية.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


