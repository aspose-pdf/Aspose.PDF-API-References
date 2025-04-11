---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: طريقة DictionaryEditor. تزيل العنصر الذي يحمل المفتاح المحدد من DictionaryEditor
type: docs
weight: 140
url: /ar/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

تزيل العنصر الذي يحمل المفتاح المحدد من [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | المفتاح الخاص بالعنصر الذي سيتم إزالته. |

### Return Value

True إذا تم إزالة العنصر بنجاح؛ وإلا، false. هذه الطريقة تعيد أيضًا false إذا لم يتم العثور على المفتاح في القاموس الأصلي أو إذا كان المفتاح غير قابل للتعديل.

### See Also

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

تزيل أول ظهور لكائن محدد من [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | الكائن الذي سيتم إزالته من [`DictionaryEditor`](../). |

### Return Value

true إذا تم إزالة العنصر بنجاح من [`DictionaryEditor`](../)؛ وإلا، false. هذه الطريقة تعيد أيضًا false إذا لم يتم العثور على العنصر في [`DictionaryEditor`](../) الأصلي.

### See Also

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)