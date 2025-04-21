---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تنسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات. ملاحظة فقط لحقول AcroForm 
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

تنسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات. ملاحظة: فقط لحقول AcroForm (باستثناء مربع الراديو).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | اسم مستند PDF الذي يحتوي على الحقل المراد نسخه. |
| fieldName | String | الاسم الكامل المؤهل للحقل الأصلي. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

تنسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية. ملاحظة: فقط لحقول AcroForm (باستثناء مربع الراديو).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | اسم مستند PDF الذي يحتوي على الحقل المراد نسخه. |
| fieldName | String | الاسم الكامل المؤهل للحقل الأصلي. |
| pageNum | Int32 | رقم الصفحة التي ستحتوي على الحقل الجديد. إذا كان -1، سيتم نسخ الحقل الجديد إلى نفس الصفحة التي استضافها القديم. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

تنسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات. ملاحظة: فقط لحقول AcroForm (باستثناء مربع الراديو).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | اسم مستند PDF الذي يحتوي على الحقل المراد نسخه. |
| fieldName | String | الاسم الكامل المؤهل للحقل الأصلي. |
| pageNum | Int32 | رقم الصفحة التي ستحتوي على الحقل الجديد. إذا كان -1، سيتم نسخ الحقل الجديد إلى نفس الصفحة التي استضافها القديم. |
| abscissa | Single | الإحداثي السيني للحقل الجديد. إذا كان -1، سيكون الإحداثي السيني مساويًا للأصلي. |
| ordinate | Single | الإحداثي الصادي للحقل الجديد. إذا كان -1، سيكون الإحداثي الصادي مساويًا للأصلي. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)