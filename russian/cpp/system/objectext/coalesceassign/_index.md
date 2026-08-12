---
title: "Метод System::ObjectExt::CoalesceAssign"
linktitle: "CoalesceAssign"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ObjectExt::CoalesceAssign. Реализация перевода оператора ''??='' в C++."
type: docs
weight: 600
url: /ru/cpp/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign method


Реализация перевода оператора '??='.

```cpp
template<typename T0,typename T1> static T0 & System::ObjectExt::CoalesceAssign(T0 &value, T1 func)
```


| Параметр | Описание |
| --- | --- |
| T0 | Тип значения LHS. |
| T1 | Тип лямбда-выражения, инкапсулирующего RHS. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T0\& | Значение LHS. |
| func | T1 | Выражение RHS. |

### ReturnValue

Если значение LHS не равно null, возвращает LHS, иначе вычисляет выражение RHS и возвращает результат.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
