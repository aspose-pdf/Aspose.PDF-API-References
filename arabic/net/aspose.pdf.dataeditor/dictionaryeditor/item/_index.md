---
title: DictionaryEditor.Item
second_title: Aspose.PDF for .NET API Reference
description: خاصية DictionaryEditor. تحصل أو تعين العنصر بالمفتاح المحدد
type: docs
weight: 50
url: /ar/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## فهرس DictionaryEditor

تحصل أو تعين العنصر بالمفتاح المحدد.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| المعامل | الوصف |
| --- | --- |
| key | المفتاح الخاص بالعنصر الذي ترغب في الحصول عليه أو تعيينه. |

### قيمة الإرجاع

العنصر بالمفتاح المحدد.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentNullException | المفتاح فارغ. |
| KeyNotFoundException | تم استرجاع الخاصية والمفتاح غير موجود. |
| ArgumentException | إلقاء استثناء إذا لم يكن بالإمكان تعديل/تعيين المفتاح. |

### انظر أيضًا

* الواجهة [ICosPdfPrimitive](../../icospdfprimitive/)
* الفئة [DictionaryEditor](../)
* مساحة الاسم [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* التجميع [Aspose.PDF](../../../)