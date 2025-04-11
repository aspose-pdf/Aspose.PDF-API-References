---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. ملء حقل الباركود وفقًا لاسم الحقل المؤهل بالكامل
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/form/fillbarcodefield/
---
## طريقة Form.FillBarcodeField

ملء حقل الباركود وفقًا لاسم الحقل المؤهل بالكامل.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل المؤهل بالكامل. |
| data | سلسلة | قيمة الباركود الجديدة. |

### قيمة الإرجاع

إذا تم الملء بنجاح، ارجع true؛ خلاف ذلك، false.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)