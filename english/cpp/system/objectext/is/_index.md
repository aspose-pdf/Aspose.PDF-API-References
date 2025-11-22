---
title: System::ObjectExt::Is method
linktitle: Is
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt::Is method. Implements ''is'' operator translation. Specialization for string literal in C++.'
type: docs
weight: 1000
url: /cpp/system/objectext/is/
---
## ObjectExt::Is(const char16_t *) method


Implements 'is' operator translation. Specialization for string literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const ExceptionWrapper\<U\>\&) method


Implements 'is' operator translation. Specialization for exception wrapper types.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const ExceptionWrapper\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Nullable\<U\>\&) method


Implements 'is' operator translation. Specialization for [Nullable](../../nullable/) type.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Nullable\<U\>\& | [Nullable](../../nullable/) type. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Object\&) method


Implements 'is' operator translation. Specialization for value types.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const Object\&) method


Implements 'is' operator translation. Specialization for unconvertible types.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const Object\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

Always returns false as types are unconvertible.

## See Also

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implements 'is' operator translation. Specialization for nullable types.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implements 'is' operator translation. Specialization for boxable types with == operator defined.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<Object\>\&) method


Implements 'is' operator translation. Specialization for boxable types without defined ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<U\>\&) method


Implements 'is' operator translation. Specialization for enum types.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const SmartPtr\<V\>\&) method


Implements 'is' operator translation. Specialization value types boxed to interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |
| V | Type of the pointed object. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const SmartPtr\<V\>\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [Object](../../object/)
* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const T\&) method


Implements 'is' operator translation. Specialization for boxable (value) types which exactly is that they are.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to test for 'is' operator. Ignored. |

### ReturnValue

Always true

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const U\&) method


Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Tested type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const U\&) method


Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Tested type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(const WeakPtr\<U\>\&) method


Implements 'is' operator translation. Specialization for enum types vs weak pointers.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const WeakPtr\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [WeakPtr](../../weakptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Is(int32_t) method


Implements 'is' operator translation. Specialization for integer literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


| Parameter | Description |
| --- | --- |
| T | Target type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | int32_t | integer literal. |

### ReturnValue

True if 'is' returns true, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
