---
title: "Form.GetButtonOptionCurrentValue"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تُرجع القيمة الحالية لحقول خيارات زر الراديو"
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue method

يعيد القيمة الحالية لحقول خيارات زر الراديو.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل |

### قيمة الإرجاع

قيمة سلسلة للمجموعة الراديوية الحالية. راجع أيضًا [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


