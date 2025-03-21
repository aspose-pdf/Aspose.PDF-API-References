---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageCollection class. Collection of PDF document pages
type: docs
weight: 8080
url: /net/aspose.pdf/pagecollection/
---
## PageCollection class

Collection of PDF document pages.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Gets count of pages in the document. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Gets value indicating of collection is readonly. Always returns false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Returns true of object is synchorinzed. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Gets page by index. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Gets synchronization object of the collection. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Accepts [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) visitor object that provides functionality to work with annotations. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Accepts [`ImagePlacementAbsorber`](../imageplacementabsorber/) visitor object that provides functionality to work with image placement objects. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Accepts [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) visitor object that provides functionality to work with text objects. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Accepts [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) visitor object that provides functionality to work with text objects. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Adds to collection all pages from list. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Adds page to collection. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Adds to collection all pages from array. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Clear page collection. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Determines whether this instance contains the object. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Copyies pages into document. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Deletes all pages from collection. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Delete specified page. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Delete pages specified which numbers are specified in array. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Removes all fields located on the pages and place their values instead. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Clears cached data |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Returns enumerator of pages. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Returns index of the specified page. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Inserts pages from the collection into document. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Inserts page into page collection at specified place. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Inserts pages of the array into document. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Removes the specified item, throws NotSupportedException. |

### See Also

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


