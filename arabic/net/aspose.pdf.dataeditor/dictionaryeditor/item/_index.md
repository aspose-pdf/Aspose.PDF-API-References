---
title: "DictionaryEditor.Item"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية DictionaryEditor. تحصل أو تعيّن العنصر بالمفتاح المحدد."
type: docs
weight: 50
url: /ar/net/aspose.pdf.dataeditor/dictionaryeditor/item/
---
## DictionaryEditor indexer

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
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


