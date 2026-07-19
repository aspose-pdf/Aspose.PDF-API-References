---
title: "System::Array::FindAll method"
linktitle: "FindAll"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Array::FindAll method. Получает все элементы, соответствующие условиям, определённым указанным предикатом, в C++."
type: docs
weight: 5400
url: /ru/cpp/system/array/findall/
---
## Array::FindAll method


Получает все элементы, соответствующие условиям, определённым указанным предикатом.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) для поиска элементов в |
| соответствие | System::Predicate\<T\> | Предикат, определяющий условия для сопоставления элементов массива |

### ReturnValue

Массив [Array](../), содержащий все элементы, соответствующие условиям, определённым указанным предикатом, если такие найдены; в противном случае — пустой [Array](../).

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
