---
title: "Form.GetField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تحصل على قيمة الحقل وفقًا لاسم الحقل."
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

يحصل على قيمة الحقل وفقًا لاسمه.

```csharp
public string GetField(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل. |

### قيمة الإرجاع

قيمة الحقل.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


