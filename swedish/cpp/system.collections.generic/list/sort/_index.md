---
title: "System::Collections::Generic::List::Sort method"
linktitle: "Sortera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::List::Sort‑metod. Sorterar element i listan med standardkomparator i C++."
type: docs
weight: 4400
url: /sv/cpp/system.collections.generic/list/sort/
---
## List::Sort() method


Sorterar element i listan med standardjämförare.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## Se även

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(Comparison\<T\>, bool) method


Sorterar element i listan.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comparison | Comparison\<T\> | [Comparison](../../../system/comparison/) att använda. |

## Se även

* Class [Comparison](../../../system/comparison/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Sorterar element i listan.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| komparator | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | Komparator att använda. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) method


Sorterar element i listsegmentet.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Skivans startindex. |
| count | int | Skivans storlek. |
| komparator | SharedPtr\<System::Collections::Generic::IComparer\<T\>\> | Komparator att använda. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
