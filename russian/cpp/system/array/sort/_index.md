---
title: "System::Array::Sort метод"
linktitle: "Сортировать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Array::Sort. Сортирует два массива: один, содержащий ключи, и другой — соответствующие элементы, основываясь на значениях массива с ключами, элементы которого сравниваются с помощью оператора< в C++."
type: docs
weight: 6000
url: /ru/cpp/system/array/sort/
---
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method


Сортирует два массива, один содержащий ключи и другой - соответствующие элементы, основываясь на значениях массива, содержащего ключи, элементы которого сравниваются с помощью оператора<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


| Параметр | Описание |
| --- | --- |
| TKey | Тип элементов в массиве **keys** |
| TValue | тип элементов в массиве **items** |

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) содержащий значения ключей |
| items | const ArrayPtr\<TValue\>\& | [Array](../) содержащий элементы, сопоставленные со значениями ключей в массиве **keys** |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method


Сортирует два массива, один содержащий ключи и другой - соответствующие элементы, основываясь на значениях массива, содержащего ключи, элементы которого сравниваются с помощью сравнивателя по умолчанию.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


| Параметр | Описание |
| --- | --- |
| TKey | Тип элементов в массиве **keys** |
| TValue | тип элементов в массиве **items** |

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) содержащий значения ключей |
| items | const ArrayPtr\<TValue\>\& | [Array](../) содержащий элементы, сопоставленные со значениями ключей в массиве **keys** |
| индекс | int | Индекс, обозначающий начало диапазона для сортировки |
| длина | int | Количество элементов в диапазоне для сортировки |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&) method


Сортирует элементы в указанном массиве, используя сравниватель по умолчанию.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Целевой массив |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Сортирует элементы в указанном массиве, используя указанный сравниватель.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Целевой массив |
| компаратор | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | Объект IComparer<T>, используемый для сравнения элементов массива |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method


НЕ РЕАЛИЗОВАНО.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) method


Сортирует элементы в указанном массиве, используя указанное сравнение.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Comparison](../../comparison/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method


Сортирует диапазон элементов в указанном массиве, используя сравниватель по умолчанию.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Целевой массив |
| startIndex | int | Индекс, обозначающий начало диапазона элементов для сортировки |
| count | int | Размер диапазона элементов для сортировки |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
