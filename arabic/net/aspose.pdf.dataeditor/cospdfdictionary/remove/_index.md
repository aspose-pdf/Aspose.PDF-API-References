---
title: CosPdfDictionary.Remove
second_title: Aspose.PDF for .NET API Reference
description: طريقة CosPdfDictionary. يزيل العنصر الذي يحمل المفتاح المحدد من CosPdfDictionary
type: docs
weight: 150
url: /ar/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

يزيل العنصر الذي يحمل المفتاح المحدد من [`CosPdfDictionary`](../).

```csharp
public bool Remove(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | المفتاح الخاص بالعنصر الذي سيتم إزالته. |

### Return Value

صحيح إذا تم إزالة العنصر بنجاح؛ خلاف ذلك، خطأ. تعيد هذه الطريقة أيضًا خطأ إذا لم يتم العثور على المفتاح في القاموس الأصلي أو إذا كان المفتاح غير قابل للتعديل.

### See Also

* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

يزيل أول ظهور لكائن محدد من [`CosPdfDictionary`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | الكائن الذي سيتم إزالته من [`CosPdfDictionary`](../). |

### Return Value

صحيح إذا تم إزالة العنصر بنجاح من [`CosPdfDictionary`](../)؛ خلاف ذلك، خطأ. تعيد هذه الطريقة أيضًا خطأ إذا لم يتم العثور على العنصر في [`CosPdfDictionary`](../) الأصلي.

### See Also

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)