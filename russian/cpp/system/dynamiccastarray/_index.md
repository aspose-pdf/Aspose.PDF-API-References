---
title: "System::DynamicCastArray method"
linktitle: "DynamicCastArray"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::DynamicCastArray method. Выполняет приведение элементов указанного массива к другому типу в C++."
type: docs
weight: 18400
url: /ru/cpp/system/dynamiccastarray/
---
## System::DynamicCastArray method


Выполняет приведение элементов указанного массива к другому типу.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


| Параметр | Описание |
| --- | --- |
| К | Тип, к которому следует привести элементы указанного массива |
| От | Тип элементов массива, элементы которого необходимо привести |

| Параметр | Тип | Описание |
| --- | --- | --- |
| от | const SharedPtr\<Array\<From\>\>\& | Умный указатель на массив, содержащий элементы для приведения |

### ReturnValue

Указатель на новый массив, содержащий элементы типа **To**, эквивалентные элементам **from**

## Deprecated
Добавлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
