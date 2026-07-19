---
title: "Метод Aspose::Pdf::PageCollection::Insert"
linktitle: "Вставить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::PageCollection::Insert. Вставляет пустую страницу в коллекцию в указанной позиции. Если документ уже содержит страницы разных размеров, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы в C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.pdf/pagecollection/insert/
---
## PageCollection::Insert(int32_t) method


Вставляет пустую страницу в коллекцию в указанную позицию. Если документ уже содержит страницы разных размеров, будет выбран размер наиболее часто встречающейся страницы. В случае, когда существует только две разные страницы, будет использован размер первой страницы.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int32_t | Позиция новой страницы. |

### ReturnValue

Вставленная страница.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::ArrayPtr\<System::SharedPtr\<Page\>\>\&) method


Вставляет страницы из массива в документ.

```cpp
void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::ArrayPtr<System::SharedPtr<Page>> &pages)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int32_t | Начальный номер новых страниц. |
| страницы | const System::ArrayPtr\<System::SharedPtr\<Page\>\>\& | Массив страниц, которые будут вставлены. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::SharedPtr\<Page\>\&) method


Вставляет страницу в коллекцию страниц в указанное место.

```cpp
System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::SharedPtr<Page> &entity)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int32_t | Требуемый индекс страницы в коллекции. |
| entity | const System::SharedPtr\<Page\>\& | [Page](../../page/) для вставки. |

### ReturnValue

Вставленная страница.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\&) method


Вставляет страницы из коллекции в документ.

```cpp
void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> &pages)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int32_t | Начальная позиция новых страниц. |
| страницы | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>\& | Коллекция страниц. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
