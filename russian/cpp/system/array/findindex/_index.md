---
title: "Метод System::Array::FindIndex"
linktitle: "FindIndex"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Array::FindIndex. Ищет первый элемент в указанном массиве, который удовлетворяет условиям заданного предиката в C++."
type: docs
weight: 5500
url: /ru/cpp/system/array/findindex/
---
## Array::FindIndex method


Ищет первый элемент в указанном массиве, который удовлетворяет условиям указанного предиката.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) для поиска элемента в |
| соответствие | System::Predicate\<T\> | Предикат, определяющий условия для сопоставления элементов массива |

### ReturnValue

Индекс первого элемента в массиве, который удовлетворяет условиям, определённым предикатом, иначе -1

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
