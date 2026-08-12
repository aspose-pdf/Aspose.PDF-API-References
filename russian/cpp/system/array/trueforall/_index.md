---
title: "Метод System::Array::TrueForAll"
linktitle: "TrueForAll"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Array::TrueForAll. Определяет, удовлетворяют ли все элементы в указанном массиве условиям, определённым заданным предикатом в C++."
type: docs
weight: 6100
url: /ru/cpp/system/array/trueforall/
---
## Array::TrueForAll method


Определяет, удовлетворяют ли все элементы в указанном массиве условиям, определённым указанным предикатом.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) элементы, которые необходимо сопоставить с условиями |
| соответствие | System::Predicate\<T\> | Предикат, определяющий условия для сопоставления элементов массива |

### ReturnValue

true, если все элементы массива arr удовлетворяют условиям, определённым предикатом match, иначе false

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
