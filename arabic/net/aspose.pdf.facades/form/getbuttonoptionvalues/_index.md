---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تحصل على حقول خيارات زر الراديو والقيم ذات الصلة بناءً على اسم الحقل. هذه الطريقة لها معنى لمجموعات زر الراديو
type: docs
weight: 190
url: /ar/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## طريقة Form.GetButtonOptionValues

تحصل على حقول خيارات زر الراديو والقيم ذات الصلة بناءً على اسم الحقل. هذه الطريقة لها معنى لمجموعات زر الراديو.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل |

### قيمة الإرجاع

جدول تجزئة لقيم الخيارات مفاتيحها باسم عنصر النموذج

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### انظر أيضًا

* الفئة [Form](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)