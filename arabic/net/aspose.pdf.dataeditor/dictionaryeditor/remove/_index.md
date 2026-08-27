---
title: "DictionaryEditor.Remove"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة DictionaryEditor. يزيل العنصر بالمفتاح المحدد من DictionaryEditor"
type: docs
weight: 140
url: /ar/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

يزيل العنصر بالمفتاح المحدد من [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | String | المفتاح للعنصر المراد إزالته. |

### قيمة الإرجاع

صحيح إذا تم إزالة العنصر بنجاح؛ وإلا، خطأ. تُعيد هذه الطريقة أيضًا خطأ إذا لم يُعثر على المفتاح في القاموس الأصلي أو إذا كان المفتاح غير قابل للتحرير

### انظر أيضًا

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

يزيل أول تكرار لكائن محدد من [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| item | KeyValuePair`2 | الكائن لإزالته من [`DictionaryEditor`](../). |

### قيمة الإرجاع

صحيح إذا تم إزالة العنصر بنجاح من [`DictionaryEditor`](../)؛ وإلا، خطأ. تُعيد هذه الطريقة أيضًا خطأ إذا لم يُعثر على العنصر في [`DictionaryEditor`](../) الأصلي.

### انظر أيضًا

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


