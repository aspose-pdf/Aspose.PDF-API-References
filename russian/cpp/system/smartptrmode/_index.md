---
title: "System::SmartPtrMode enum"
linktitle: "SmartPtrMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::SmartPtrMode enum. Тип указателя SmartPtr: слабый или разделяемый. Определяет, учитывается ли указатель при решении, удалять объект или нет в C++."
type: docs
weight: 8800
url: /ru/cpp/system/smartptrmode/
---
## SmartPtrMode enum


[SmartPtr](../smartptr/) pointer type: weak or shared. Defines whether pointer is being counted when it is being decided whether to delete object or not.

```cpp
enum class SmartPtrMode : char
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Разделяемый | 0 | Режим разделяемый: указатель участвует в подсчёте ссылок. |
| Weak | 1 | Режим слабый: указатель не участвует в подсчёте ссылок. |

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
