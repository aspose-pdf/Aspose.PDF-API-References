---
title: "Метод System::ObjectExt::CoalesceInternal"
linktitle: "CoalesceInternal"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::ObjectExt::CoalesceInternal. Реализация перевода оператора ''??'' для не‑nullable типов. Перегрузка для случая, когда RT2 преобразуем к RT1 в C++."
type: docs
weight: 700
url: /ru/cpp/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal method


Реализация перевода оператора '??' для типов, не допускающих null. Перегрузка для случая, когда RT2 преобразуем к RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


| Параметр | Описание |
| --- | --- |
| T0 | Тип значения LHS. |
| T1 | Тип лямбда-выражения, инкапсулирующего RHS. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | RT1 | Значение LHS. |
| func | F | Выражение RHS. |

### ReturnValue

Если значение LHS не равно null, возвращает LHS, иначе вычисляет выражение RHS и возвращает результат.

## См. также

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
