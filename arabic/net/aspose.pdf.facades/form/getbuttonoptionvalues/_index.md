---
title: "Form.GetButtonOptionValues"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. يحصل على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. هذه الطريقة ذات معنى لمجموعات أزرار الراديو"
type: docs
weight: 190
url: /ar/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues method

يحصل على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. لهذه الطريقة معنى في مجموعات أزرار الراديو.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل |

### قيمة الإرجاع

جدول تجزئة لقيم الخيارات مفتاحه اسم عنصر النموذج

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


