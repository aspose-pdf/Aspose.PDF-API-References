---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تقوم بتسطيح حقل محدد باسم الحقل المؤهل بالكامل. سيبقى أي حقل آخر غير قابل للتغيير. إذا كان اسم الحقل غير صالح، ستبقى جميع الحقول غير قابلة للتغيير.
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/form/flattenfield/
---
## طريقة Form.FlattenField

تقوم بتسطيح حقل محدد باسم الحقل المؤهل بالكامل. سيبقى أي حقل آخر غير قابل للتغيير. إذا كان اسم الحقل غير صالح، ستبقى جميع الحقول غير قابلة للتغيير.

```csharp
public void FlattenField(string fieldName)
```

| المعامل | النوع | الوصف |
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