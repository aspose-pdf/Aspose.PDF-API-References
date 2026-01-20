---
title: Aspose::Pdf::PageCollection::Insert method
linktitle: Insert
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageCollection::Insert method. Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf/pagecollection/insert/
---
## PageCollection::Insert(int32_t) method


Insert an empty page into the collection at the specified position. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | Position of the new page. |

### ReturnValue

Inserted page.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, System::ArrayPtr\<System::SharedPtr\<Page\>\>) method


Inserts pages of the array into document.

```cpp
void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, System::ArrayPtr<System::SharedPtr<Page>> pages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | Starting number of the new pages. |
| pages | System::ArrayPtr\<System::SharedPtr\<Page\>\> | Array of pages which will be inserted. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, System::SharedPtr\<Page\>) method


Inserts page into page collection at specified place.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, System::SharedPtr<Page> entity)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | Required page index in collection. |
| entity | System::SharedPtr\<Page\> | [Page](../../page/) to be inserted. |

### ReturnValue

Inserted page.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>) method


Inserts pages from the collection into document.

```cpp
void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> pages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | Starting position of the new pages. |
| pages | System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\> | Pages collection. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
