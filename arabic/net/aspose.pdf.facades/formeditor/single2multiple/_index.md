---
title: Single2Multiple
second_title: Aspose.PDF لمرجع .NET API
description: قم بتغيير حقل نص أحادي السطر إلى حقل متعدد الأسطر.
type: docs
weight: 390
url: /ar/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

قم بتغيير حقل نص أحادي السطر إلى حقل متعدد الأسطر.

```csharp
public bool Single2Multiple(string fieldName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |

### قيمة الإرجاع

إذا نجحت ، أرجع صحيحًا وإلا خطأ.

### أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### أنظر أيضا

* class [FormEditor](../../formeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../formeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
