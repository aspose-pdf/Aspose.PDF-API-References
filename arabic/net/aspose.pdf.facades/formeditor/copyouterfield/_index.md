---
title: "FormEditor.CopyOuterField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تنسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع الحفاظ على رقم الصفحة الأصلي والإحداثيات. ملاحظة: فقط لحقول AcroForm باستثناء مربع الراديو."
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الاختيار).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcFileName | String | اسم مستند PDF الذي يحتوي على الحقل المراد نسخه. |
| fieldName | String | الاسم الأصلي المؤهل بالكامل للحقل. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//ينسخ حقل النص من source.pdf إلى PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الاختيار).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcFileName | String | اسم مستند PDF الذي يحتوي على الحقل المراد نسخه. |
| fieldName | String | الاسم الأصلي المؤهل بالكامل للحقل. |
| pageNum | Int32 | عدد الصفحة التي ستحمل الحقل الجديد. إذا كان -1، سيتم نسخ الحقل الجديد إلى نفس الصفحة التي يستضيفها القديم. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة والإحداثيات المحددة. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الاختيار).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcFileName | String | اسم مستند PDF الذي يحتوي على الحقل المراد نسخه. |
| fieldName | String | الاسم الأصلي المؤهل بالكامل للحقل. |
| pageNum | Int32 | عدد الصفحة التي ستحمل الحقل الجديد. إذا كان -1، سيتم نسخ الحقل الجديد إلى نفس الصفحة التي يستضيفها القديم. |
| الإحداثي السيني | Single | الإحداثي السيني للحقل الجديد. إذا كان -1، سيُساوي الإحداثي السيني الأصلي. |
| الإحداثي الصادي | Single | الإحداثي الصادي للحقل الجديد. إذا كان -1، سيُساوي الإحداثي الصادي الأصلي. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


