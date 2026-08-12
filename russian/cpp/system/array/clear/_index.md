---
title: "Метод System::Array::Clear"
linktitle: "Clear"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Array::Clear. Не поддерживается, потому что массив, представленный текущим объектом, является только для чтения в C++."
type: docs
weight: 600
url: /ru/cpp/system/array/clear/
---
## Array::Clear() method


Не поддерживается, поскольку массив, представленный текущим объектом, доступен только для чтения.

```cpp
virtual void System::Array<T>::Clear() override
```


## См. также

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Clear(const ArrayPtr\<Type\>\&, int, int) method


Заменяет **count** значений, начиная с индекса **startIndex**, в указанном массиве значениями по умолчанию.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


| Параметр | Описание |
| --- | --- |
| Тип | Тип элементов в целевом массиве |

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Целевой массив |
| startIndex | int | [Index](../../index/) с которого начинать замену элементов |
| count | int | Количество элементов для замены |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
