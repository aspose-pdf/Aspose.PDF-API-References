---
title: System::operator== method
linktitle: operator==
second_title: Aspose.PDF for C++ API Reference
description: 'How to use operator== method of  class in C++.'
type: docs
weight: 32400
url: /cpp/system/operator==/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) method




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## See Also

* Class [ArraySegment](../arraysegment/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(Chars\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


| Parameter | Description |
| --- | --- |
| Chars | [String](../string/) literal type. |

| Parameter | Type | Description |
| --- | --- | --- |
| left | Chars\& | [String](../string/) literal to compare. |
| right | const String\& | [String](../string/) to compare. |

### ReturnValue

true if strings match, false otherwise.

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const SharedPtr\<Object\>\&, const String\&) method


[Object](../object/) and string comparison.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


| Parameter | Type | Description |
| --- | --- | --- |
| left | const SharedPtr\<Object\>\& | [Object](../object/) to convert to string and compare. |
| right | const String\& | [String](../string/) to compare. |

### ReturnValue

true if object string representation equals to string, false otherwise.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) method


Determines if the URIs represented by the current and specified objects are equal.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | The first [Uri](../uri/) object to compare |
| uri2 | const SharedPtr\<Uri\>\& | The second [Uri](../uri/) object to compare |

### ReturnValue

True if URIs are equal, otherwise - false

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Uri](../uri/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) method


Equal-compares two smart pointers.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


| Parameter | Description |
| --- | --- |
| X | Pointee type of first pointer. |
| Y | Pointee type of second pointer. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | First pointer to compare. |
| y | const SmartPtr\<Y\>\& | Second pointer to compare. |

### ReturnValue

True if pointers match, false otherwise.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const SmartPtr\<X\>\&, const Y *) method


Equality comparison smart pointer against simple (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


| Parameter | Description |
| --- | --- |
| X | type of smart pointer. |
| Y | type of simple pointer. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const SmartPtr\<X\>\& | smart pointer to compare (left). |
| y | const Y * | pointer to compare (right). |

### ReturnValue

True if pointers match, false otherwise.

## See Also

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const T1\&, const Nullable\<T2\>\&) method


Determines if the specified value is equal to the value represented by the specified [Nullable](../nullable/) object by applying [operator==()](./) to these values.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const Nullable\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### ReturnValue

True if the comparands are equal, otherwise - false

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(const X *, const SmartPtr\<Y\>\&) method


Equality comparison smart pointer against simple (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


| Parameter | Description |
| --- | --- |
| X | type of simple pointer. |
| Y | type of smart pointer. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | const X * | pointer to compare (right). |
| y | const SmartPtr\<Y\>\& | smart pointer to compare (left). |

### ReturnValue

True if pointers match, false otherwise.

## See Also

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, const DateTimeOffset\&) method




```cpp
bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## See Also

* Class [DateTimeOffset](../datetimeoffset/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, const Nullable\<T\>\&) method


Determines if the specified [Nullable](../nullable/) object represents a value that is equal to null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


| Parameter | Type | Description |
| --- | --- | --- |
| other | std::nullptr_t | A constant reference to an [Nullable](../nullable/) object to test |

### ReturnValue

True if the specified object represents null value, false otherwise

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, const String\&) method


Checks if string is null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) to check. |

### ReturnValue

true if string is null, false otherwise.

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, DateTime) method




```cpp
bool System::operator==(std::nullptr_t, DateTime)
```

## See Also

* Class [DateTime](../datetime/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) method


Checks if smart pointer is null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


| Parameter | Description |
| --- | --- |
| X | Pointee type of pointer. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | std::nullptr_t | Pointer to check. |

### ReturnValue

True if pointer is null, false otherwise.

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, T const\&) method


Checks if value type object (translated C# structure, etc.) is null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


| Parameter | Description |
| --- | --- |
| T | Value type. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) to check. |

### ReturnValue

True if object is null, false otherwise.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(std::nullptr_t, TimeSpan) method




```cpp
bool System::operator==(std::nullptr_t, TimeSpan)
```

## See Also

* Class [TimeSpan](../timespan/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(T\&, const String\&) method


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


| Parameter | Description |
| --- | --- |
| T | [String](../string/) pointer type. |

| Parameter | Type | Description |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer to compare. |
| right | const String\& | [String](../string/) to compare. |

### ReturnValue

true if strings match, false otherwise.

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::operator==(T const\&, std::nullptr_t) method


Checks if value type object (translated C# structure, etc.) is null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


| Parameter | Description |
| --- | --- |
| T | Value type. |

| Parameter | Type | Description |
| --- | --- | --- |
| x | T const\& | [Object](../object/) to check. |

### ReturnValue

True if object is null, false otherwise.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
