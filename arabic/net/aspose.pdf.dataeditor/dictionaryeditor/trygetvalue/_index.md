---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: طريقة DictionaryEditor. للوصول إلى نوع البيانات البسيطة مثل الاسم من نوع سلسلة، بول، رقم. تعيد null للأنواع الأخرى
type: docs
weight: 150
url: /ar/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## طريقة DictionaryEditor.TryGetValue

للوصول إلى نوع البيانات البسيطة مثل السلسلة، الاسم، البول، الرقم. تعيد null للأنواع الأخرى.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| key | String | قيمة المفتاح |
| value | ICosPdfPrimitive& | تعيد [`ICosPdfPrimitive`](../../icospdfprimitive/) للمفتاح أو null. |

### قيمة الإرجاع

تعيد true إذا كانت [`ICosPdfPrimitive`](../../icospdfprimitive/) مثل السلسلة، الاسم، البول، الرقم. تعيد false لجميع الأنواع الأخرى.

### انظر أيضًا

* الواجهة [ICosPdfPrimitive](../../icospdfprimitive/)
* الفئة [DictionaryEditor](../)
* مساحة الاسم [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* التجميع [Aspose.PDF](../../../)