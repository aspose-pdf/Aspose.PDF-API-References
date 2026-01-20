---
title: System::operator+ method
linktitle: operator+
second_title: Aspose.PDF for C++ API Reference
description: 'System::operator+ method. String concatenation in C++.'
type: docs
weight: 27500
url: /cpp/system/operator+/
---
## System::operator+(const char_t, const String\&) method


[String](../string/) concatenation.

```cpp
String System::operator+(const char_t left, const String &right)
```


| Parameter | Type | Description |
| --- | --- | --- |
| left | const char_t | Character to concatenate to string. |
| right | const String\& | [String](../string/) to concatenate. |

### ReturnValue

Concatenated string.

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(const T\&, const Decimal\&) method


Returns a new instance of [Decimal](../decimal/) class that represents a value that is a sum of the specified value and the value represented by the specified [Decimal](../decimal/) object.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | const T\& | The first summand |
| d | const Decimal\& | The constant reference to the [Decimal](../decimal/) object representing the second summand |

### ReturnValue

A new instance of [Decimal](../decimal/) class that represents a value that is a sum of **x** and the value represented by the **d**.

## See Also

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(const T1\&, const Nullable\<T2\>\&) method


Sums non-nullable and nullable values.

```cpp
template<typename T1,typename T2,typename> System::Nullable<decltype(some+other.get_Value())> System::operator+(const T1 &some, const Nullable<T2> &other)
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

Summing result.

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) method


Connects all callbacks from right hand delegate to the end of left hand delegate callback list.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


| Parameter | Type | Description |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | The delegate to which callbacks are added. |
| rhv | MulticastDelegate\<T\> | The delegate whose callbacks are being added. |

### ReturnValue

Returns a delegate that contains the callbacks of the left hand value and then the right hand ones.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(T\&, const String\&) method


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


| Parameter | Description |
| --- | --- |
| T | [String](../string/) literal type. |

| Parameter | Type | Description |
| --- | --- | --- |
| left | T\& | Literal to concatenate to string. |
| right | const String\& | [String](../string/) to concatenate. |

### ReturnValue

Concatenated string.

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator+(T\&, const String\&) method


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


| Parameter | Description |
| --- | --- |
| T | [String](../string/) pointer type. |

| Parameter | Type | Description |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer to concatenate to string. |
| right | const String\& | [String](../string/) to concatenate. |

### ReturnValue

Concatenated string.

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
