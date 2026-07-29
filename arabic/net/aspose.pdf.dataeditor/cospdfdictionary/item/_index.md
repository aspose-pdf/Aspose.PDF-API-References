---
title: "CosPdfDictionary.Item"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية CosPdfDictionary. تحصل على العنصر بالمفتاح المحدد أو تعينه."
type: docs
weight: 60
url: /ar/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## CosPdfDictionary indexer

يحصل أو يضبط العنصر بالمفتاح المحدد.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| المفتاح | المفتاح للعنصر المراد الحصول عليه أو تعيينه. |

### قيمة الإرجاع

العنصر بالمفتاح المحدد.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المفتاح هو null. |
| KeyNotFoundException | يتم استرجاع الخاصية ولا يتم العثور على المفتاح. |
| ArgumentException | ارمِ استثناءً إذا تعذر تعديل/تعيين المفتاح. |

### انظر أيضًا

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


