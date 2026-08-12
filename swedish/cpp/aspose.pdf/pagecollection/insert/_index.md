---
title: "Aspose::Pdf::PageCollection::Insert metod"
linktitle: "Infoga"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageCollection::Insert metod. Infogar en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med olika storlekar kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf/pagecollection/insert/
---
## PageCollection::Insert(int32_t) method


Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med olika storlekar kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int32_t | Position för den nya sidan. |

### ReturnValue

Infogad sida.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) method


Infogar sidor från arrayen i dokumentet.

```cpp
void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::ArrayPtr<System::SharedPtr<Page>> &pages)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int32_t | Startnummer för de nya sidorna. |
| sidor | const System::ArrayPtr\<System::SharedPtr\<Page\>\>\& | Array av sidor som kommer att infogas. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::SharedPtr\<Page\>\&) method


Infogar en sida i sidssamlingen på angiven plats.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::SharedPtr<Page> &entity)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int32_t | Krävt sidindex i samlingen. |
| entity | const System::SharedPtr\<Page\>\& | [Page](../../page/) att infogas. |

### ReturnValue

Infogad sida.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) method


Infogar sidor från samlingen i dokumentet.

```cpp
void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> &pages)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int32_t | Startposition för de nya sidorna. |
| sidor | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\& | Sidsamling. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
