---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: خاصية CosPdfDictionary. يحصل على العنصر أو يضبطه باستخدام المفتاح المحدد
type: docs
weight: 60
url: /ar/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## فهرس CosPdfDictionary

يحصل على العنصر أو يضبطه باستخدام المفتاح المحدد.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| المعامل | الوصف |
| --- | --- |
| key | المفتاح الخاص بالعنصر الذي سيتم الحصول عليه أو ضبطه. |

### قيمة الإرجاع

العنصر الذي يحمل المفتاح المحدد.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | المفتاح فارغ. |
| KeyNotFoundException | تم استرجاع الخاصية والمفتاح غير موجود. |
| ArgumentException | إلقاء استثناء إذا لم يكن بالإمكان تعديل/ضبط المفتاح. |

### انظر أيضًا

* الواجهة [ICosPdfPrimitive](../../icospdfprimitive/)
* الفئة [CosPdfDictionary](../)
* مساحة الاسم [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* التجميع [Aspose.PDF](../../../)