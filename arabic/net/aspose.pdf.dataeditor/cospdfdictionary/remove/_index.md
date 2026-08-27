---
title: "CosPdfDictionary.Remove"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة CosPdfDictionary. تزيل العنصر بالمفتاح المحدد من CosPdfDictionary"
type: docs
weight: 150
url: /ar/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

تزيل العنصر بالمفتاح المحدد من [`CosPdfDictionary`](../).

```csharp
public bool Remove(string key)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | String | المفتاح للعنصر المراد إزالته. |

### قيمة الإرجاع

صحيح إذا تم إزالة العنصر بنجاح؛ وإلا، خطأ. تُعيد هذه الطريقة أيضًا خطأ إذا لم يُعثر على المفتاح في القاموس الأصلي أو إذا كان المفتاح غير قابل للتحرير

### انظر أيضًا

* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

تزيل الظهور الأول لكائن محدد من [`CosPdfDictionary`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| item | KeyValuePair`2 | الكائن المراد إزالته من [`CosPdfDictionary`](../). |

### قيمة الإرجاع

true إذا تم إزالة العنصر بنجاح من [`CosPdfDictionary`](../)؛ وإلا false. تُعيد هذه الطريقة أيضًا false إذا لم يُعثر على العنصر في [`CosPdfDictionary`](../) الأصلي.

### انظر أيضًا

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


