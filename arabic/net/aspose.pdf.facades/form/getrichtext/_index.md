---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. احصل على قيمة حقول النص الغني بما في ذلك معلومات التنسيق لكل حرف
type: docs
weight: 260
url: /ar/net/aspose.pdf.facades/form/getrichtext/
---
## طريقة Form.GetRichText

احصل على قيمة حقل النص الغني، بما في ذلك معلومات التنسيق لكل حرف.

```csharp
public string GetRichText(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | الاسم المؤهل بالكامل لحقل النص الغني. |

### قيمة الإرجاع

إرجاع سلسلة تحتوي على معلومات التنسيق لحقل النص الغني.

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)