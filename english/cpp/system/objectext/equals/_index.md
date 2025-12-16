---
title: System::ObjectExt::Equals method
linktitle: Equals
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::Equals method. Substitution for C# Object.Equals calls working for any type in C++. Overload for string literal with string comparison in C++.'
type: docs
weight: 800
url: /cpp/system/objectext/equals/
---
## ObjectExt::Equals(const char_t(&), String) method


Substitution for C# [Object.Equals](../../object/equals/) calls working for any type in C++. Overload for string literal with string comparison.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


| Parameter | Description |
| --- | --- |
| N | [String](../../string/) literal size. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | String | [String](../../string/). |

### ReturnValue

True if strings match, false otherwise.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const double\&, const double\&) method


Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


| Parameter | Type | Description |
| --- | --- | --- |
| obj | const double\& | LHS floating point value. |
| another | const double\& | RHS floating point value. |

### ReturnValue

True if **obj** and **another** are both NaN or equal, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const float\&, const float\&) method


Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


| Parameter | Type | Description |
| --- | --- | --- |
| obj | const float\& | LHS floating point value. |
| another | const float\& | RHS floating point value. |

### ReturnValue

True if **obj** and **another** are both NaN or equal, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Substitution for C# [Object.Equals](../../object/equals/) calls working for any type in C++. Overload for smart pointer types.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### ReturnValue

True if objects are considered equal, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Substitution for C# [Object.Equals](../../object/equals/) calls working for any type in C++. Overload for scalar types.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### ReturnValue

True if objects are considered equal, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Equals(T, const T2\&) method


Substitution for C# [Object.Equals](../../object/equals/) calls working for any type in C++. Overload for structure types.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | First object. |
| another | const T2\& | Second object. |

### ReturnValue

True if objects are considered equal, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
