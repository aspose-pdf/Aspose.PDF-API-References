---
title: "DictionaryEditor.TryGetValue"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة DictionaryEditor. للوصول إلى نوع بيانات بسيط مثل string name bool number. تُرجع null للأنواع الأخرى"
type: docs
weight: 150
url: /ar/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue method

للوصول إلى أنواع البيانات البسيطة مثل السلسلة، الاسم، bool، الرقم. يرجع null للأنواع الأخرى.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | String | قيمة المفتاح |
| value | ICosPdfPrimitive& | تُرجع [`ICosPdfPrimitive`](../../icospdfprimitive/) للمفتاح أو null. |

### قيمة الإرجاع

تُرجع true إذا كان [`ICosPdfPrimitive`](../../icospdfprimitive/) من نوع string أو name أو bool أو number. تُرجع false لجميع الأنواع الأخرى.

### انظر أيضًا

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


