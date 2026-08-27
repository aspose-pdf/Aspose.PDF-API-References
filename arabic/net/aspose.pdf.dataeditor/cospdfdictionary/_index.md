---
title: "الفئة CosPdfDictionary"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.DataEditor.CosPdfDictionary. فئة للوصول إلى قاموس كائنات"
type: docs
weight: 3540
url: /ar/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class

فئة للوصول إلى قاموس كائن

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | ينشئ قاموسًا من الموارد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | مجموعة كاملة من المفاتيح. تحتوي على مفاتيح قابلة للتحرير وغير قابلة للتحرير. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | يحصل على عدد العناصر الموجودة في `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كان `CosPdfDictionary` للقراءة فقط. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | يحصل أو يضبط العنصر بالمفتاح المحدد. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | مجموعة من المفاتيح القابلة للتحرير. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | يحصل على ICollection يحتوي على القيم في `CosPdfDictionary`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | ينشئ قاموسًا فارغًا سيتم ربطه بالمستند. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | ينشئ قاموسًا فارغًا سيتم ربطه بالصفحة. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | عيّن [`ICosPdfPrimitive`](../icospdfprimitive/) إلى القاموس. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | عيّن [`ICosPdfPrimitive`](../icospdfprimitive/) إلى القاموس. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | يزيل جميع العناصر من `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | يحدد ما إذا كان `CosPdfDictionary` يحتوي على قيمة محددة. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | يحدد ما إذا كان `CosPdfDictionary` يحتوي على عنصر بالمفتاح المحدد. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | يرجع عدّادًا يتنقل عبر المجموعة. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | يزيل أول ظهور لكائن محدد من `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | يزيل العنصر بالمفتاح المحدد من `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | يحاول تحويل هذه النسخة إلى [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | يحاول تحويل هذا الكائن إلى `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | يحاول تحويل هذه النسخة إلى [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | يحاول تحويل هذه النسخة إلى [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | يحاول تحويل هذا الكائن إلى [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | للوصول إلى أنواع البيانات البسيطة مثل السلسلة، الاسم، bool، الرقم. يرجع null للأنواع الأخرى. |

### انظر أيضًا

* class [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


