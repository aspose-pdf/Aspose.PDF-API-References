---
title: Aspose::Pdf::PageCollection::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageCollection::Add method. Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/pagecollection/add/
---
## PageCollection::Add() method


Adds an empty page. If the document already contains pages with varying sizes, the size of the most frequently occurring page will be selected. In the case there are only two different pages, the size of the first page will be used.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Add()
```


### ReturnValue

Added page.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) method


Adds to collection all pages from array.

```cpp
void Aspose::Pdf::PageCollection::Add(const System::ArrayPtr<System::SharedPtr<Page>> &pages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pages | const System::ArrayPtr\<System::SharedPtr\<Page\>\>\& | Array of pages which will be added. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) method


Adds to collection all pages from list.

```cpp
void Aspose::Pdf::PageCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> &pages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pages | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\& | List which contains all pages which must be added. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
