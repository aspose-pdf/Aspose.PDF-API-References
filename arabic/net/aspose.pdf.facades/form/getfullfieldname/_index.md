---
title: "Form.GetFullFieldName"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تحصل على الاسم الكامل للحقل وفقًا لاسمه المختصر."
type: docs
weight: 250
url: /ar/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

يحصل على الاسم الكامل للحقول بناءً على اسمها المختصر.

```csharp
public string GetFullFieldName(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل. |

### قيمة الإرجاع

الاسم الكامل للحقل.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


