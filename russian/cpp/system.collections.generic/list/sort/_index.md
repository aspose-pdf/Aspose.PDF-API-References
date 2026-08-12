---
title: "System::Collections::Generic::List::Sort метод"
linktitle: "Сортировать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::List::Sort метод. Сортирует элементы в списке, используя компаратор по умолчанию в C++."
type: docs
weight: 4400
url: /ru/cpp/system.collections.generic/list/sort/
---
## List::Sort() method


Сортирует элементы в списке, используя компаратор по умолчанию.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## См. также

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(Comparison\<T\>, bool) method


Сортирует элементы в списке.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| comparison | Comparison\<T\> | [Comparison](../../../system/comparison/) для использования. |

## См. также

* Class [Comparison](../../../system/comparison/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Сортирует элементы в списке.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| компаратор | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | Компаратор для использования. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) method


Сортирует элементы в срезе списка.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс начала среза. |
| count | int | Размер среза. |
| компаратор | SharedPtr\<System::Collections::Generic::IComparer\<T\>\> | Компаратор для использования. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
