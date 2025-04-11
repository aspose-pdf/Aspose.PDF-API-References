---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. الحصول على حد حقل النص
type: docs
weight: 230
url: /ar/net/aspose.pdf.facades/form/getfieldlimit/
---
## طريقة Form.GetFieldLimit

الحصول على حد حقل النص.

```csharp
public int GetFieldLimit(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل المؤهل. |

### قيمة الإرجاع

إرجاع عدد الأحرف التي يمكن ملؤها في حقل النص. إذا لم يتم تعيينه، إرجع 0.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### انظر أيضًا

* الفئة [Form](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)