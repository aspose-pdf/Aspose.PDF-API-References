---
title: "System::Array::Find метод"
linktitle: "Find"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Array::Find. Ищет первый элемент в указанном массиве, который удовлетворяет условиям заданного предиката в C++."
type: docs
weight: 5300
url: /ru/cpp/system/array/find/
---
## Array::Find method


Ищет первый элемент в указанном массиве, который удовлетворяет условиям указанного предиката.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) для поиска элемента в |
| соответствие | System::Predicate\<T\> | Предикат, определяющий условия для сопоставления элементов массива |

### ReturnValue

Копия первого элемента массива, который удовлетворяет условиям, определённым предикатом, иначе значение по умолчанию типа T

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
