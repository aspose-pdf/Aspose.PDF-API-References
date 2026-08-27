---
title: "الفئة PageCollection"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.PageCollection. مجموعة من صفحات مستند PDF"
type: docs
weight: 8220
url: /ar/net/aspose.pdf/pagecollection/
---
## PageCollection class

مجموعة من صفحات مستند PDF.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | يحصل على عدد الصفحات في المستند. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | يحصل على القيمة التي تشير إلى أن المجموعة للقراءة فقط. دائمًا ما تُعيد false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | تُعيد true إذا كان الكائن متزامنًا. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | يحصل على الصفحة حسب الفهرس. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | يحصل على كائن المزامنة للمجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | يقبل كائن الزائر [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) الذي يوفر وظيفة للعمل مع التعليقات التوضيحية. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | يقبل كائن الزائر [`ImagePlacementAbsorber`](../imageplacementabsorber/) الذي يوفر وظيفة للعمل مع كائنات وضع الصور. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | يقبل كائن الزائر [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) الذي يوفر وظيفة للعمل مع كائنات النص. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | يقبل كائن الزائر [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) الذي يوفر وظيفة للعمل مع كائنات النص. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة التي تظهر أكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيتم استخدام حجم الصفحة الأولى. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | يضيف إلى المجموعة جميع الصفحات من القائمة. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | يضيف صفحة إلى المجموعة. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | يضيف إلى المجموعة جميع الصفحات من المصفوفة. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | مسح مجموعة الصفحات. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | يحدد ما إذا كانت هذه الحالة تحتوي على الكائن. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | ينسخ الصفحات إلى المستند. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | يحذف جميع الصفحات من المجموعة. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | احذف الصفحة المحددة. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | احذف الصفحات المحددة التي أرقامها محددة في المصفوفة. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | يزيل جميع الحقول الموجودة على الصفحات ويضع قيمها بدلاً منها. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | يمسح البيانات المخزنة مؤقتًا |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | يعيد المُعدد للصفحات. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | يعيد فهرس الصفحة المحددة. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | أدرج صفحة فارغة في المجموعة في الموضع المحدد. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة الأكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيُستخدم حجم الصفحة الأولى. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | يدرج الصفحات من المجموعة في المستند. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | يدرج صفحة في مجموعة الصفحات في المكان المحدد. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | يدرج الصفحات الموجودة في المصفوفة في المستند. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | يزيل العنصر المحدد، ويرمي NotSupportedException. |

### انظر أيضًا

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


