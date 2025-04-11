---
title: CosPdfDictionary.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: طريقة CosPdfDictionary. للوصول إلى نوع بيانات بسيط مثل سلسلة، اسم، بول، رقم. ترجع null لأنواع أخرى
type: docs
weight: 170
url: /ar/net/aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/
---
## طريقة CosPdfDictionary.TryGetValue

للوصول إلى نوع بيانات بسيط مثل سلسلة، اسم، بول، رقم. ترجع null لأنواع أخرى.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| key | String | قيمة المفتاح |
| value | ICosPdfPrimitive& | ترجع [`ICosPdfPrimitive`](../../icospdfprimitive/) للمفتاح أو null. |

### قيمة الإرجاع

ترجع true إذا كانت [`ICosPdfPrimitive`](../../icospdfprimitive/) مثل سلسلة، اسم، بول، رقم. ترجع false لجميع الأنواع الأخرى.

### انظر أيضًا

* واجهة [ICosPdfPrimitive](../../icospdfprimitive/)
* فئة [CosPdfDictionary](../)
* مساحة الاسم [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* التجميع [Aspose.PDF](../../../)