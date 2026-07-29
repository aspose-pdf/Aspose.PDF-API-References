---
title: "Form.FlattenField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تقوم بتسطيح حقل محدد باستخدام الاسم المؤهل بالكامل للحقل. سيبقى أي حقل آخر غير قابل للتغيير. إذا كان fieldName غير صالح، سيبقى جميع الحقول غير قابلة للتغيير."
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

يقوم بتسطيح حقل محدد باستخدام اسمه الكامل المؤهل. ستبقى جميع الحقول الأخرى غير قابلة للتغيير. إذا كان اسم الحقل غير صالح، ستبقى جميع الحقول غير قابلة للتغيير.

```csharp
public void FlattenField(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي سيتم تسطيحه. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


