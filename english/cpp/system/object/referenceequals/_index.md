---
title: System::Object::ReferenceEquals method
linktitle: ReferenceEquals
second_title: Aspose.PDF for C++ API Reference
description: 'System::Object::ReferenceEquals method. Specialization of Object::ReferenceEquals for case of string and nullptr in C++.'
type: docs
weight: 1200
url: /cpp/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) method


Specialization of [Object::ReferenceEquals](./) for case of string and nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | String const\& | [String](../../string/) to compare to nullptr. |

### ReturnValue

true if string is null, false otherwise.

## See Also

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(String const\&, String const\&) method


Specialization of [Object::ReferenceEquals](./) for case of strings.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str1 | String const\& | First string to compare. |
| str2 | String const\& | Second string to compare. |

### ReturnValue

true if strings match, false otherwise.

## See Also

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(ptr const\&, ptr const\&) method


Compares objects by reference.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


| Parameter | Type | Description |
| --- | --- | --- |
| objA | ptr const\& | First pointer to compare. |
| objB | ptr const\& | Second pointer to compare. |

### ReturnValue

True if pointers match and false otherwise.

## See Also

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(T const\&, std::nullptr_t) method


Reference-compares value type object with nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


| Parameter | Description |
| --- | --- |
| T | Type of object to compare. |

| Parameter | Type | Description |
| --- | --- | --- |
| objA | T const\& | First object to compare. |

### ReturnValue

Always returns false as value types cannot be nulled.

## See Also

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(T const\&, T const\&) method


Compares objects by reference.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


| Parameter | Description |
| --- | --- |
| T | Type of objects to compare. |

| Parameter | Type | Description |
| --- | --- | --- |
| objA | T const\& | First object to compare. |
| objB | T const\& | Second object to compare. |

### ReturnValue

True if object addresses match and false otherwise.

## See Also

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
