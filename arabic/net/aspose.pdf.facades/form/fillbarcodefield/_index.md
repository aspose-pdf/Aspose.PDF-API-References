---
title: FillBarcodeField
second_title: Aspose.PDF لمرجع .NET API
description: املأ حقل الباركود وفقًا لاسم الحقل المؤهل بالكامل.
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

املأ حقل الباركود وفقًا لاسم الحقل المؤهل بالكامل.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل. |
| data | String | قيمة الباركود الجديد. |

### قيمة الإرجاع

إذا نجح الملء ، فارجع إلى صحيح خلاف ذلك ، خطأ.

### أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### أنظر أيضا

* class [Form](../../form)
* مساحة الاسم [Aspose.Pdf.Facades](../../form)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->