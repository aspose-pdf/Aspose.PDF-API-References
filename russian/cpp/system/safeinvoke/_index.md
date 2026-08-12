---
title: "System::SafeInvoke method"
linktitle: "SafeInvoke"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::SafeInvoke method. Реализация перевода оператора ''?.'' в C++."
type: docs
weight: 37700
url: /ru/cpp/system/safeinvoke/
---
## System::SafeInvoke method


Реализация перевода оператора '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


| Параметр | Описание |
| --- | --- |
| T0 | тип выражения. |
| T1 | Тип лямбда‑выражения, инкапсулирующего выражение 'WhenTrue'. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| expr | T0\\&& | значение выражения. |
| func | T1\\&& | Выражение 'WhenTrue', привязанное к функтору. |

### ReturnValue

Если значение expr не равно null, возвращает func, вызванный с этим значением в качестве первого аргумента, иначе возвращает null.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
