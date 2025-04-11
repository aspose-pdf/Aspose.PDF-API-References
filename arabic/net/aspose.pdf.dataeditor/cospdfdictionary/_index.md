---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.DataEditor.CosPdfDictionary. فئة للوصول إلى قاموس الكائنات
type: docs
weight: 3420
url: /ar/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class

فئة للوصول إلى قاموس كائن.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Constructors

| Name | Description |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | ينشئ قاموسًا من الموارد. |

## Properties

| Name | Description |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | مجموعة كاملة من المفاتيح. تحتوي على مفاتيح قابلة للتعديل وغير قابلة للتعديل. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | يحصل على عدد العناصر الموجودة في `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كان `CosPdfDictionary` للقراءة فقط. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | يحصل أو يحدد العنصر بالمفتاح المحدد. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | مجموعة من المفاتيح القابلة للتعديل. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | يحصل على ICollection تحتوي على القيم في `CosPdfDictionary`. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | ينشئ قاموسًا فارغًا سيتم إرفاقه بالمستند. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | ينشئ قاموسًا فارغًا سيتم إرفاقه بالصفحة. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | تعيين [`ICosPdfPrimitive`](../icospdfprimitive/) إلى القاموس. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | تعيين [`ICosPdfPrimitive`](../icospdfprimitive/) إلى القاموس. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | يزيل جميع العناصر من `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | يحدد ما إذا كان `CosPdfDictionary` يحتوي على قيمة معينة. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | يحدد ما إذا كان `CosPdfDictionary` يحتوي على عنصر بالمفتاح المحدد. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | يعيد عدادًا يتكرر عبر المجموعة. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | يزيل أول ظهور لكائن معين من `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | يزيل العنصر بالمفتاح المحدد من `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | يحاول تحويل هذه الحالة إلى [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | يحاول تحويل هذه الحالة إلى `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | يحاول تحويل هذه الحالة إلى [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | يحاول تحويل هذه الحالة إلى [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | يحاول تحويل هذه الحالة إلى [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | للوصول إلى نوع البيانات البسيط مثل السلسلة، الاسم، البوليان، الرقم. يعيد null للأنواع الأخرى. |

### See Also

* class [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)