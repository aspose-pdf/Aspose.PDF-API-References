---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تعيد القيمة الحالية لحقول خيارات زر الراديو
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## طريقة Form.GetButtonOptionCurrentValue

تعيد القيمة الحالية لحقول خيارات زر الراديو.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل |

### قيمة الإرجاع

قيمة سلسلة لمجموعة زر الراديو الحالية. انظر أيضًا [`GetButtonOptionValues`](../getbuttonoptionvalues/)

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### انظر أيضًا

* الفئة [Form](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)