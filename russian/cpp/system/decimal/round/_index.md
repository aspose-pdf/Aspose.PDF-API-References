---
title: "метод System::Decimal::Round"
linktitle: "Round"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Decimal::Round method. Округляет указанное значение до ближайшего значения с указанным числом знаков после запятой. Параметр определяет поведение функции, если указанное значение равноценно близко к двум ближайшим числам в C++."
type: docs
weight: 4400
url: /ru/cpp/system/decimal/round/
---
## Decimal::Round(const Decimal\&, int, MidpointRounding) method


Округляет указанное значение до ближайшего значения с указанным числом знаков после запятой. Параметр определяет поведение функции, если указанное значение одинаково близко к двум ближайшим числам.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| d | const Decimal\& | Значение для округления |
| знаков | int | Количество знаков после запятой в округленном значении |
| режим | MidpointRounding | Указывает, как выполнять округление, если **value** равноценно близко к двум ближайшим числам. |

### ReturnValue

Число с указанным количеством знаков, ближайшее к **value**

## См. также

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::Round(const Decimal\&, MidpointRounding) method


Округляет указанное значение до ближайшего целого числа. Параметр определяет поведение функции, если указанное значение одинаково близко к двум ближайшим числам.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| d | const Decimal\& | Значение для округления |
| режим | MidpointRounding | Указывает, как выполнять округление, если **value** равноценно близко к двум ближайшим числам. |

### ReturnValue

**d** rounded to the nearest integral value

## См. также

* Class [Decimal](../)
* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
