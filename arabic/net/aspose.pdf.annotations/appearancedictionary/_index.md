---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.AppearanceDictionary. قاموس مظهر التعليق يحدد كيف يجب تقديم التعليق بصريًا على الصفحة
type: docs
weight: 1490
url: /ar/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

قاموس مظهر التعليق يحدد كيف يجب تقديم التعليق بصريًا على الصفحة.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | يحصل على عدد العناصر الموجودة في القاموس. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | يحصل على قيمة تشير إلى ما إذا كان القاموس له حجم ثابت. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كان القاموس للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى القاموس متزامنًا (آمن للخيوط). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | يمثل شكلًا مريحًا للحصول على تدفقات المظهر. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | يحصل على مفاتيح القاموس. إذا كان قاموس المظهر يحتوي على قواميس فرعية، فإن [`Keys`](./keys/) تحتوي على قيم (N&#x7C;R&#x7C;D).state، حيث N - المظهر العادي، R - مظهر التمرير، D - المظهر المنخفض وstate - اسم الحالة (مثل On، Off لصناديق الاختيار). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى القاموس. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | يحصل على قائمة بقيم القاموس. تحتوي مجموعة النتائج على قائمة من كائنات XForm. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | يضيف زوجًا مع مفتاح وقيمة إلى القاموس. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | أضف نموذج X للمفتاح المحدد. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | يزيل جميع العناصر من القاموس. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | يتحقق مما إذا كان زوج المفتاح والقيمة المحدد موجودًا في القاموس. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | ينسخ عناصر القاموس إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | يعيد كائن IDictionaryEnumerator للقاموس. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | يزيل المفتاح من القاموس. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها. |

### See Also

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)