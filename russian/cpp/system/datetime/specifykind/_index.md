---
title: "Метод System::DateTime::SpecifyKind"
linktitle: "SpecifyKind"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::DateTime::SpecifyKind. Создаёт новый объект DateTime, который представляет то же количество тиков, что и указанный объект DateTime, и представляет локальное время, время UTC или ни то ни другое в зависимости от аргумента kind в C++."
type: docs
weight: 6800
url: /ru/cpp/system/datetime/specifykind/
---
## DateTime::SpecifyKind method


Создаёт новый объект [DateTime](../), который представляет то же количество тиков, что и указанный объект [DateTime](../), и представляет локальное время, время UTC или ни то ни другое в зависимости от аргумента **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | DateTime | Объект [DateTime](../), из которого копировать количество тиков. |
| вид | DateTimeKind | Указывает, должно ли новый объект представлять локальное время, время UTC или ни то ни другое. |

### ReturnValue

Новый объект [DateTime](../), который представляет то же количество тиков, что и **value**, и значение [DateTimeKind](../../datetimekind/), указанное в **kind**.

## См. также

* Class [DateTime](../)
* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
