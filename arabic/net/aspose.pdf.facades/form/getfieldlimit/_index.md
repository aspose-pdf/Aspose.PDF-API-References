---
title: "Form.GetFieldLimit"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. احصل على حد حقل النص"
type: docs
weight: 230
url: /ar/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit method

احصل على قيود حقل النص.

```csharp
public int GetFieldLimit(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |

### قيمة الإرجاع

تُرجع عدد الأحرف الحد الأقصى الذي يمكن ملء حقل النص به. إذا لم يُحدد، تُرجع 0.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


