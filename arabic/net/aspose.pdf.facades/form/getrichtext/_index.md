---
title: "Form.GetRichText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. احصل على قيمة حقل Rich Text بما في ذلك معلومات التنسيق لكل حرف"
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText method

احصل على قيمة حقل النص الغني، بما في ذلك معلومات التنسيق لكل حرف.

```csharp
public string GetRichText(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | الاسم المؤهل بالكامل لحقل Rich Text. |

### قيمة الإرجاع

إرجاع سلسلة تحتوي على معلومات التنسيق لحقل Rich Text.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


