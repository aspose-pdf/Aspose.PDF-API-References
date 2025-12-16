---
title: Aspose::Pdf::PageCollection class
linktitle: PageCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageCollection class. Collection of PDF document pages in C++.'
type: docs
weight: 13400
url: /cpp/aspose.pdf/pagecollection/
---
## PageCollection class


[Collection](../collection/) of PDF document pages.

```cpp
class PageCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Page>>,
                       public Aspose::Pdf::ISupportsMemoryCleanup
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<Annotations::AnnotationSelector\>) | Accepts [AnnotationSelector](../) visitor object that provides functionality to work with annotations. |
| [Accept](./accept/)(System::SharedPtr\<ImagePlacementAbsorber\>) | Accepts [ImagePlacementAbsorber](../imageplacementabsorber/) visitor object that provides functionality to work with image placement objects. |
| [Accept](./accept/)(System::SharedPtr\<Text::TextFragmentAbsorber\>) | Accepts [TextFragmentAbsorber](../) visitor object that provides functionality to work with text objects. |
| [Accept](./accept/)(System::SharedPtr\<Text::TextAbsorber\>) | Accepts [TextAbsorber](../) visitor object that provides functionality to work with text objects. |
| [Add](./add/)() | Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [Add](./add/)(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) | Adds to collection all pages from list. |
| [Add](./add/)(const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) | Adds to collection all pages from array. |
| [Clear](./clear/)() override | Clear page collection. |
| [Contains](./contains/)(const System::SharedPtr\<Page\>\&) const override | Determines whether this instance contains the object. |
| [CopyPage](./copypage/)(System::SharedPtr\<Page\>) | Adds page to collection. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Page\>\>, int32_t) override | Copyies pages into document. |
| [Delete](./delete/)(int32_t) | Delete specified page. |
| [Delete](./delete/)() | Deletes all pages from collection. |
| [Delete](./delete/)(System::ArrayPtr\<int32_t\>) | Delete pages specified which numbers are specified in array. |
| [Flatten](./flatten/)() | Removes all fields located on the pages and place their values instead. |
| [FreeMemory](./freememory/)() override | Clears cached data. |
| [get_Count](./get_count/)() const override | Gets count of pages in the document. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets value indicating of collection is readonly. Always returns false. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true of object is synchorinzed. |
| [get_SyncRoot](./get_syncroot/)() const | Gets synchronization object of the collection. |
| [GetEnumerator](./getenumerator/)() override | Returns enumerator of pages. |
| [idx_get](./idx_get/)(int32_t) | Gets page by index. |
| [IndexOf](./indexof/)(System::SharedPtr\<Page\>) const | Returns index of the specified page. |
| [Insert](./insert/)(int32_t) | Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<Page\>) | Inserts page into page collection at specified place. |
| [Insert](./insert/)(int32_t, System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>) | Inserts pages from the collection into document. |
| [Insert](./insert/)(int32_t, System::ArrayPtr\<System::SharedPtr\<Page\>\>) | Inserts pages of the array into document. |
| [Remove](./remove/)(const System::SharedPtr\<Page\>\&) override | Removes the specified item, throws NotSupportedException
. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
