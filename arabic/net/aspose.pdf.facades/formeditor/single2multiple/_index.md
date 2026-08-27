---
title: "FormEditor.Single2Multiple"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تحويل حقل نصي بسطر واحد إلى حقل متعدد الأسطر"
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

تحويل حقل نص أحادي السطر إلى حقل نص متعدد الأسطر.

```csharp
public bool Single2Multiple(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |

### قيمة الإرجاع

إذا نجح، إرجاع true؛ وإلا false.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


