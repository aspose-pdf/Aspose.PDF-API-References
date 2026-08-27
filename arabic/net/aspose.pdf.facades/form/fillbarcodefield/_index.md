---
title: "Form.FillBarcodeField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. املأ حقل الباركود وفقًا لاسمه المؤهل بالكامل"
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

املأ حقل الباركود وفقًا لاسمه الكامل المؤهل.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل. |
| data | String | قيمة الباركود الجديدة. |

### قيمة الإرجاع

إذا نجح التعبئة، تُرجع true؛ وإلا، false.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


