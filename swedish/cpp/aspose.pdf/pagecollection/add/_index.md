---
title: "Aspose::Pdf::PageCollection::Add metod"
linktitle: "Add"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageCollection::Add metod. Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/pagecollection/add/
---
## PageCollection::Add() method


Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar väljs storleken på den mest förekommande sidan. Om det bara finns två olika sidor används storleken på den första sidan.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Add()
```


### ReturnValue

Tillagd sida.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) method


Lägger till alla sidor från arrayen i samlingen.

```cpp
void Aspose::Pdf::PageCollection::Add(const System::ArrayPtr<System::SharedPtr<Page>> &pages)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sidor | const System::ArrayPtr\<System::SharedPtr\<Page\>\>\& | Array med sidor som kommer att läggas till. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) method


Lägger till alla sidor från listan i samlingen.

```cpp
void Aspose::Pdf::PageCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> &pages)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sidor | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\& | Lista som innehåller alla sidor som måste läggas till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
