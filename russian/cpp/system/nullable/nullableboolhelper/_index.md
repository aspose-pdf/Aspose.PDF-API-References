---
title: "System::Nullable::NullableBoolHelper method"
linktitle: "NullableBoolHelper"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::NullableBoolHelper method. Вспомогательная функция для проверки, что this и other оба не null, и вызова лямбда‑функции в этом случае. Используется в реализации на C++."
type: docs
weight: 800
url: /ru/cpp/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper method


Вспомогательная функция для проверки, что this и **other** оба не null и вызова лямбда‑выражения, если это так. Используется в реализации.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Другой nullable тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | const T1\& | Другое nullable значение для сравнения. |
| f | const std::function\<bool()>\& | Лямбда‑функция, вызываемая, если оба **this** и **other** не null. |
| default_if_both_are_null | bool | Возвращаемое значение, если оба значения равны null. |

### ReturnValue

false, если любой из **this** или **other** равен null; **default_if_both_are_null**, если оба равны null; результат вызова **f**, если оба не null.

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
