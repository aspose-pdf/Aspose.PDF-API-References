---
title: AppearanceDictionary
second_title: Aspose.PDF لمرجع .NET API
description: قاموس مظهر التعليقات التوضيحية يحدد كيفية تقديم التعليق التوضيحي بشكل مرئي على الصفحة.
type: docs
weight: 160
url: /ar/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

قاموس مظهر التعليقات التوضيحية يحدد كيفية تقديم التعليق التوضيحي بشكل مرئي على الصفحة.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count) { get; } | الحصول على عدد العناصر الموجودة في القاموس. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize) { get; } | الحصول على قيمة تشير إلى ما إذا كان القاموس بحجم ثابت. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly) { get; } | يحصل على قيمة تشير إلى ما إذا كان القاموس للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى القاموس متزامنًا (مؤشر ترابط آمن). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item) { get; set; } | يمثل نموذجًا مناسبًا للحصول على تيارات المظهر. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys) { get; } | يحصل على مفاتيح القاموس. إذا كان قاموس المظهر يحتوي على أقسام فرعية ، فحينئذٍ[`Keys`](./keys)يحتوي على (N &#x7C; R &#x7C; D). قيم الحالة ، حيث N - المظهر الطبيعي ، R - مظهر التمرير ، D - المظهر والحالة - اسم state (على سبيل المثال ، تشغيل ، إيقاف تشغيل لمربعات الاختيار) . |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى القاموس. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values) { get; } | يحصل على قائمة بقيم القاموس. تحتوي مجموعة النتائج على قائمة كائنات XForm. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add#add)(KeyValuePair&lt;string, XForm&gt;) | إضافة زوج بالمفتاح والقيمة إلى القاموس. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add#add_2)(string, XForm) | أضف نموذج X للمفتاح المحدد. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear)() | يزيل كل العناصر من القاموس. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains)(KeyValuePair&lt;string, XForm&gt;) | الشيكات لا يتم تضمين زوج قيمة مفتاح محدد في القاموس. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey)(string) | يحدد هل يحتوي هذا القاموس على مفتاح محدد. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto#copyto)(XForm[], int) | ينسخ عناصر القاموس إلى مصفوفة ، بدءًا من فهرس مصفوفة معين. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator)() | إرجاع كائن IDictionaryEnumerator للقاموس. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove#remove)(KeyValuePair&lt;string, XForm&gt;) | يزيل زوج المفتاح / القيمة من المجموعة. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove#remove_1)(string) | إزالة المفتاح من القاموس. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue)(string, out XForm) | يحاول العثور على مفتاح في القاموس ويستعيد القيمة إذا تم العثور عليه. |

### أنظر أيضا

* class [XForm](../../aspose.pdf/xform)
* مساحة الاسم [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->