---
title: "PageCollection Class"
linktitle: "PageCollection"
articleTitle: "PageCollection"
second_title: "Aspose.PDF for .NET"
description: "Collection of PDF document pages."
type: docs
weight: 2140
url: "/net/aspose.pdf/pagecollection/"
keywords: "PageCollection, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PageCollection class

[Collection](../collection/) of PDF document pages.

```csharp
public sealed class PageCollection : IEnumerable
```

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets count of pages in the document. |
| [IsReadOnly](./isreadonly/) { get; } | Gets value indicating of collection is readonly. Always returns false. |
| [IsSynchronized](./issynchronized/) { get; } | Returns true of object is synchorinzed. |
| [Item](./item/) { get; } |  |
| [SyncRoot](./syncroot/) { get; } | Gets synchronization object of the collection. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*AnnotationSelector*) | Accepts [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) visitor object that provides functionality to work with annotations. |
| [Accept](./accept/)(*ImagePlacementAbsorber*) | Accepts [`ImagePlacementAbsorber`](../../aspose.pdf/imageplacementabsorber/) visitor object that provides functionality to work with image placement objects. |
| [Accept](./accept/)(*TextFragmentAbsorber*) | Accepts [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) visitor object that provides functionality to work with text objects. |
| [Accept](./accept/)(*TextAbsorber*) | Accepts [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) visitor object that provides functionality to work with text objects. |
| [Accept](./accept/)(*OcrTextAbsorber*) | Accepts an [`OcrTextAbsorber`](../../aspose.pdf.ocr/ocrtextabsorber/) that extracts plain text from these pages using OCR. |
| [Add](./add/) | Adds an empty page. |
| [Add](./add/)(*Page*) | Adds page to collection. |
| [Add](./add/)(*ICollection<Page>*) | Adds to collection all pages from list. |
| [Add](./add/)(*Page[]*) | Adds to collection all pages from array. |
| [BeginUpdate](./beginupdate/) | Updates when group changes begin. Stops page cache recalculation on each operation. |
| [Clear](./clear/) | Clear page collection. |
| [Contains](./contains/)(*Page*) | Determines whether this instance contains the object. |
| [CopyTo](./copyto/)(*Page[], int*) | Copyies pages into document. |
| [Delete](./delete/) | Deletes all pages from collection. |
| [Delete](./delete/)(*int*) | Delete specified page. |
| [Delete](./delete/)(*int[]*) | Delete pages specified which numbers are specified in array. |
| [EndUpdate](./endupdate/) | Updates when group changes are complete. Restores page cache recalculations on each operation. |
| [Flatten](./flatten/) | Removes all fields located on the pages and place their values instead. |
| [FreeMemory](./freememory/) | Clears cached data. |
| [GetEnumerator](./getenumerator/) | Returns enumerator of pages. |
| [IndexOf](./indexof/)(*Page*) | Returns index of the specified page. |
| [Insert](./insert/)(*int*) | Insert an empty page into the collection at the specified position. |
| [Insert](./insert/)(*int, Page*) | Inserts page into page collection at specified place. |
| [Insert](./insert/)(*int, ICollection<Page>*) | Inserts pages from the collection into document. |
| [Insert](./insert/)(*int, Page[]*) | Inserts pages of the array into document. |
| [Remove](./remove/)(*Page*) | Removes the specified item, throws NotSupportedException. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

