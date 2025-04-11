---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Metadata. توفر الوصول إلى تدفق بيانات التعريف XMP
type: docs
weight: 6950
url: /ar/net/aspose.pdf/metadata/
---
## فئة بيانات التعريف

توفر الوصول إلى تدفق بيانات التعريف XMP.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | يحصل على عدد العناصر في المجموعة. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | يحصل على قاموس حقول التمديد. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | يتحقق مما إذا كانت المجموعة ذات حجم ثابت. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | يتحقق مما إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | يتحقق مما إذا كانت المجموعة متزامنة. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | يحصل على أو يحدد البيانات من بيانات التعريف. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | يحصل على مجموعة مفاتيح بيانات التعريف. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | يحصل على مدير المساحة الاسمية. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | يحصل على كائن مزامنة المجموعة. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | يحصل على القيم في بيانات التعريف. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | يضيف زوجًا مع مفتاح وقيمة إلى القاموس. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | يضيف قيمة إلى بيانات التعريف. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | يضيف امتداد PDF إلى بيانات التعريف. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | يضيف قيمة إلى بيانات التعريف. |
| [Clear](../../aspose.pdf/metadata/clear/)() | يمسح بيانات التعريف. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | يتحقق مما إذا كان زوج المفتاح والقيمة المحدد موجودًا في القاموس. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | يتحقق مما إذا كان المفتاح موجودًا في بيانات التعريف. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | يعيد عداد القاموس. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | يعيد URI المساحة الاسمية حسب البادئة. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | يعيد البادئة حسب URI المساحة الاسمية. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | يسجل URI المساحة الاسمية. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | يسجل URI المساحة الاسمية. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | يزيل الإدخال من بيانات التعريف. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها. |

### انظر أيضًا

* الفئة [XmpValue](../xmpvalue/)
* المساحة الاسمية [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)