---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. يحصل على قيمة الحقل وفقًا لاسم الحقل
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/form/getfield/
---
## طريقة Form.GetField

يحصل على قيمة الحقل وفقًا لاسم الحقل.

```csharp
public string GetField(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل المؤهل بالكامل. |

### قيمة الإرجاع

قيمة الحقل.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### انظر أيضًا

* الفئة [Form](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)