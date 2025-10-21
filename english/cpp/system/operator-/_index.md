---
title: System::operator- method
linktitle: operator-
second_title: Aspose.PDF for C++ API Reference
description: 'System::operator- method. Returns a new instance of Decimal class that represents a value that is the result of subtraction of the value represented by the specified Decimal object from the specified value in C++.'
type: docs
weight: 26900
url: /cpp/system/operator-/
---
## System::operator-(const T\&, const Decimal\&) method


Returns a new instance of [Decimal](../decimal/) class that represents a value that is the result of subtraction of the value represented by the specified [Decimal](../decimal/) object from the specified value.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | const T\& | The value to subtract from |
| d | const Decimal\& | The [Decimal](../decimal/) object representing the subtracted value |

### ReturnValue

A new instance of [Decimal](../decimal/) class that represents a value that is the result of subtraction of the value represented by **d** from **x**.

## See Also

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(const T1\&, const Nullable\<T2\>\&) method


Subtracts non-nullable and nullable values.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some - other.get_Value())> System::operator-(const T1 &some, const Nullable<T2> &other)
```


| Parameter | Description |
| --- | --- |
| T1 | Left operand type. |
| T2 | Right operand type. |

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | Left operand. |
| other | const Nullable\<T2\>\& | Right operand. |

### ReturnValue

Substation result.

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(DayOfWeek, DayOfWeek) method


Calculates the number of days between two days of week.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | DayOfWeek | The minuend |
| b | DayOfWeek | The subtrahend |

### ReturnValue

The number of days between weekdays **a** and **b**; the return value is a negative number if *goes* after ****

## See Also

* Enum [DayOfWeek](../dayofweek/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Disconnects all callbacks in right hand delegate from the end of left hand delegate callback list.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Parameter | Type | Description |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | The delegate from which callbacks will be removed. |
| rhv | MulticastDelegate\<T\> | The delegate whose callbacks will be removed. |

### ReturnValue

Returns a delegate that contains the callbacks of the left hand value, but without the right hand value ones.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
