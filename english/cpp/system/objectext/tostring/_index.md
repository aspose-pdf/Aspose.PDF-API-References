---
title: System::ObjectExt::ToString method
linktitle: ToString
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::ToString method. Substitution for C# ToString method to work on any C++ type in C++.'
type: docs
weight: 1400
url: /cpp/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) method


Substitution for C# ToString method to work on any C++ type.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


| Parameter | Type | Description |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const Nullable\<T\>\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


| Parameter | Description |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const Nullable\<T\>\& | [Nullable](../../nullable/) object to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) value to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Smart pointer type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) value to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(const T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Structure type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Structure value to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Parameter | Description |
| --- | --- |
| T | Scalar type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\&& | Scalar value to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


| Parameter | Description |
| --- | --- |
| T | Scalar type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\&& | Scalar value to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Smart pointer type or [ExceptionWrapper](../../exceptionwrapper/). |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\& | Smart pointer or [ExceptionWrapper](../../exceptionwrapper/) to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Scalar type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\& | Scalar value to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ToString(T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Structure type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\& | Structure value to convert to string. |

### ReturnValue

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
