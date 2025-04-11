---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.PageCollection. مجموعة من صفحات مستند PDF
type: docs
weight: 8080
url: /ar/net/aspose.pdf/pagecollection/
---
## PageCollection class

مجموعة من صفحات مستند PDF.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | يحصل على عدد الصفحات في المستند. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. دائمًا ما ترجع false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | ترجع true إذا كان الكائن متزامنًا. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | يحصل على الصفحة حسب الفهرس. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | يحصل على كائن التزامن الخاص بالمجموعة. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | يقبل كائن الزائر [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) الذي يوفر وظائف للعمل مع التعليقات التوضيحية. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | يقبل كائن الزائر [`ImagePlacementAbsorber`](../imageplacementabsorber/) الذي يوفر وظائف للعمل مع كائنات وضع الصور. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | يقبل كائن الزائر [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) الذي يوفر وظائف للعمل مع كائنات النص. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | يقبل كائن الزائر [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) الذي يوفر وظائف للعمل مع كائنات النص. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | يضيف صفحة فارغة. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة الأكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيتم استخدام حجم الصفحة الأولى. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | يضيف إلى المجموعة جميع الصفحات من القائمة. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | يضيف صفحة إلى المجموعة. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | يضيف إلى المجموعة جميع الصفحات من المصفوفة. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | يمسح مجموعة الصفحات. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | يحدد ما إذا كانت هذه النسخة تحتوي على الكائن. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | ينسخ الصفحات إلى المستند. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | يحذف جميع الصفحات من المجموعة. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | يحذف الصفحة المحددة. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | يحذف الصفحات المحددة التي تم تحديد أرقامها في المصفوفة. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | يزيل جميع الحقول الموجودة على الصفحات ويضع قيمها بدلاً من ذلك. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | يمسح البيانات المخزنة مؤقتًا |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | يرجع عداد الصفحات. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | يرجع فهرس الصفحة المحددة. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | يُدخل صفحة فارغة في المجموعة في الموضع المحدد. إذا كان المستند يحتوي بالفعل على صفحات بأحجام مختلفة، سيتم اختيار حجم الصفحة الأكثر تكرارًا. في حالة وجود صفحتين مختلفتين فقط، سيتم استخدام حجم الصفحة الأولى. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | يُدخل الصفحات من المجموعة إلى المستند. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | يُدخل الصفحة في مجموعة الصفحات في المكان المحدد. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | يُدخل صفحات المصفوفة إلى المستند. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | يزيل العنصر المحدد، ويرمي NotSupportedException. |

### See Also

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)