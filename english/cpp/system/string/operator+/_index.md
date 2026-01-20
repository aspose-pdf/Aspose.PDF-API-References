---
title: System::String::operator+ method
linktitle: operator+
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::operator+ method. Adds character to the end of the string in C++.'
type: docs
weight: 2700
url: /cpp/system/string/operator+/
---
## String::operator+(char_t) const method


Adds character to the end of the string.

```cpp
String System::String::operator+(char_t x) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | char_t | Character to add. |

### ReturnValue

[String](../) concatenation result.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const String\&) const method


[String](../) concatenation operator.

```cpp
String System::String::operator+(const String &str) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | [String](../) to add to the end of current one. |

### ReturnValue

Concatenated string.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


[String](../) concatenation with string literal or character string pointer.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


| Parameter | Description |
| --- | --- |
| T | One of string literal or character string pointer forms. |

| Parameter | Type | Description |
| --- | --- | --- |
| arg | const T\& | Entity to concatenate with current string. |

### ReturnValue

Concatenated string.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


Adds reference type object string representation to the end of the string.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


| Parameter | Description |
| --- | --- |
| T | pointer type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) to convert to string using [ToString()](../tostring/) call and to add to current string. |

### ReturnValue

[String](../) concatenation result.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(const T\&) const method


Adds value type object string representation to the end of the string.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


| Parameter | Description |
| --- | --- |
| T | Value type to call [ToString()](../tostring/) upon. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) to convert to string using [ToString()](../tostring/) call and to add to current string. |

### ReturnValue

[String](../) concatenation result.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(double) const method


Adds floating point value string representation to the end of the string.

```cpp
String System::String::operator+(double d) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| d | double | Value to convert to string and to add. |

### ReturnValue

[String](../) concatenation result.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(int) const method


Adds integer value string representation to the end of the string.

```cpp
String System::String::operator+(int i) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int | Integer value to convert to string and to add. |

### ReturnValue

[String](../) concatenation result.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(int64_t) const method


Adds integer value string representation to the end of the string.

```cpp
String System::String::operator+(int64_t v) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| v | int64_t | Value to convert to string and to add to add. |

### ReturnValue

[String](../) concatenation result.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(T) const method


Adds boolean value string representation to the end of the string.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


| Parameter | Description |
| --- | --- |
| T | Value type to concatenate with string. Must be bool |

| Parameter | Type | Description |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) value to convert to string and to add. |

### ReturnValue

[String](../) concatenation result.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::operator+(uint32_t) const method


Adds unsigned integer value string representation to the end of the string.

```cpp
String System::String::operator+(uint32_t i) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | uint32_t | Value to convert to string and to add. |

### ReturnValue

[String](../) concatenation result.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
