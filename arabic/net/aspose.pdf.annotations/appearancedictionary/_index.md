---
title: "الفئة AppearanceDictionary"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Annotations.AppearanceDictionary. قاموس مظهر التعليق يحدد كيفية عرض التعليق بصريًا على الصفحة"
type: docs
weight: 1580
url: /ar/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

قاموس مظهر التعليق التوضيحي يحدد كيفية عرض التعليق بصريًا على الصفحة.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | يحصل على عدد العناصر الموجودة في القاموس. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | يحصل على قيمة تشير إلى ما إذا كان القاموس ذو حجم ثابت. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كان القاموس للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى القاموس متزامنًا (آمن للخيوط). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | يمثل صيغة مريحة للحصول على تدفقات المظهر. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | يحصل على مفاتيح القاموس. إذا كان قاموس المظهر يحتوي على قواميس فرعية، فإن [`Keys`](./keys/) يحتوي على قيم (N&#x7C;R&#x7C;D).state، حيث N - المظهر العادي، R - مظهر التمرير، D - مظهر الضغط وstate - اسم الحالة (مثل On, Off لخانات الاختيار). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى القاموس. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | يحصل على قائمة قيم القاموس. تحتوي مجموعة النتائج على قائمة كائنات XForm. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | يضيف زوجًا من المفتاح والقيمة إلى القاموس. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | أضف نموذج X للمفتاح المحدد. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | يزيل جميع العناصر من القاموس. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | ينسخ عناصر القاموس إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | يرجع كائن IDictionaryEnumerator للقاموس. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | يزيل المفتاح من القاموس. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا وُجد. |

### انظر أيضًا

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


