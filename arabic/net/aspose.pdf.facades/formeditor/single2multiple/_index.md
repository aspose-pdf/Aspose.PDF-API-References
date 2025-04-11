---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تغيير حقل نصي مفرد إلى حقل نصي متعدد
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/formeditor/single2multiple/
---
## طريقة FormEditor.Single2Multiple

تغيير حقل نصي مفرد إلى حقل نصي متعدد.

```csharp
public bool Single2Multiple(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |

### قيمة الإرجاع

إذا نجح، ارجع true؛ وإلا false.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)