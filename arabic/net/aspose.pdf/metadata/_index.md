---
title: "الفئة Metadata"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Metadata. توفر الوصول إلى تدفق بيانات XMP الوصفية."
type: docs
weight: 7090
url: /ar/net/aspose.pdf/metadata/
---
## Metadata class

يوفر الوصول إلى تدفق بيانات XMP الوصفية.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | يحصل على عدد العناصر في المجموعة. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | يحصل على القاموس الخاص بحقول الامتداد. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | يتحقق مما إذا كانت المجموعة ذات حجم ثابت. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | يتحقق مما إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | يتحقق مما إذا كانت المجموعة متزامنة. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | يحصل أو يعيّن البيانات من الوصفية. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | يسترجع مجموعة مفاتيح البيانات الوصفية. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | يسترجع مدير مساحة الأسماء. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | يسترجع كائن مزامنة المجموعة. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | يسترجع القيم في البيانات الوصفية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | يضيف زوجًا من المفتاح والقيمة إلى القاموس. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | يضيف قيمة إلى البيانات الوصفية. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | يضيف امتداد pdf إلى البيانات الوصفية. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | يضيف قيمة إلى البيانات الوصفية. |
| [Clear](../../aspose.pdf/metadata/clear/)() | يمسح البيانات الوصفية. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | يتحقق مما إذا كان المفتاح موجودًا في البيانات الوصفية. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | يرجع عداد القاموس. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | يرجع URI مساحة الاسم بناءً على البادئة. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | يرجع البادئة بناءً على URI مساحة الاسم. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | يسجل URI مساحة الاسم. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | يسجل URI مساحة الاسم. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | يزيل الإدخال من البيانات الوصفية. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا وُجد. |

### انظر أيضًا

* class [XmpValue](../xmpvalue/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


