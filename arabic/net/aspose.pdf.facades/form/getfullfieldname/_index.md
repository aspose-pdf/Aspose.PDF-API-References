---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. يحصل على الاسم الكامل للحقل وفقًا لاسم الحقل القصير
type: docs
weight: 250
url: /ar/net/aspose.pdf.facades/form/getfullfieldname/
---
## طريقة Form.GetFullFieldName

يحصل على الاسم الكامل للحقل وفقًا لاسم الحقل القصير.

```csharp
public string GetFullFieldName(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | الاسم المؤهل بالكامل للحقل. |

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