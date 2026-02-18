---
title: System::ObjectExt::Unbox method
linktitle: Unbox
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::Unbox method. Unboxes value types after converting to Object. Implementation for enum types in C++.'
type: docs
weight: 1500
url: /cpp/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxes value types after converting to [Object](../../object/). Implementation for enum types.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) to unbox. |

### ReturnValue

[Enum](../../enum/) value.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxes value types after converting to [Object](../../object/). Implementation for non-enum & non-nullable types.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Value type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) to unbox. |

### ReturnValue

Unboxed value.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxes value types after converting to [Object](../../object/). Implementation for non-enum & non-nullable types.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Value type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) to unbox. |

### ReturnValue

Unboxed value.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxes string values.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) to unbox |

### ReturnValue

[String](../../string/) representation of boxed string, can be null if boxed string was null.

## See Also

* Class [String](../../string/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(E) method


Unboxes enum types to integer.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


| Parameter | Description |
| --- | --- |
| T | Destination integer type. |
| E | Source enum type. |

| Parameter | Type | Description |
| --- | --- | --- |
| e | E | Value to unbox. |

### ReturnValue

Integer representation of enum.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(E) method


Converts enum types.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


| Parameter | Description |
| --- | --- |
| T | Destination enum type. |
| E | Source enum type. |

| Parameter | Type | Description |
| --- | --- | --- |
| e | E | Value to unbox. |

### ReturnValue

Converted enum value.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
