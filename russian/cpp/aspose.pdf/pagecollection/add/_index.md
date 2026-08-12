---
title: "Aspose::Pdf::PageCollection::Add метод"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PageCollection::Add метод. Добавляет пустую страницу. Если документ уже содержит страницы разного размера, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/pagecollection/add/
---
## PageCollection::Add() method


Добавляет пустую страницу. Если документ уже содержит страницы разного размера, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Add()
```


### ReturnValue

Страница добавлена.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) method


Добавляет в коллекцию все страницы из массива.

```cpp
void Aspose::Pdf::PageCollection::Add(const System::ArrayPtr<System::SharedPtr<Page>> &pages)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страницы | const System::ArrayPtr\<System::SharedPtr\<Page\>\>\& | Массив страниц, которые будут добавлены. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) method


Добавляет в коллекцию все страницы из списка.

```cpp
void Aspose::Pdf::PageCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> &pages)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страницы | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\& | Список, содержащий все страницы, которые необходимо добавить. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
