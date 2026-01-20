---
title: System::ObjectType::GetType method
linktitle: GetType
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectType::GetType method. Implements typeof() translation. Overload for primitive types in C++.'
type: docs
weight: 100
url: /cpp/system/objecttype/gettype/
---
## ObjectType::GetType() method


Implements typeof() translation. Overload for primitive types.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Description |
| --- | --- |
| T | Primitive type. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the type specified.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for enum types.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Description |
| --- | --- |
| T | Primitive type. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the type specified.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for structures and pointers.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Description |
| --- | --- |
| T | Primitive type. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the strcture specified.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Description |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the strcture specified.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Description |
| --- | --- |
| T | MutlicastDelegate type. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the strcture specified.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for structures and pointers.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


| Parameter | Description |
| --- | --- |
| T | Primitive type. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the strcture specified or pointee type if called for [SmartPtr](../../smartptr/).

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for uint8_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for int32_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for int64_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType() method


Implements typeof() translation. Overload for [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const String\&) method


Implements typeof() translation. Overload for string type.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


| Parameter | Description |
| --- | --- |
| T | Primitive type. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing [String](../../string/) type.

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implements typeof() translation. Overload for smart pointers.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Pointer object type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to get [TypeInfo](../../typeinfo/) for. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the final class of object passed.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implements typeof() translation. Overload for structures.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | Structure type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to get [TypeInfo](../../typeinfo/) for. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the final class of object passed.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T\&) method


Implements typeof() translation. Overload for exceptions.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


| Parameter | Description |
| --- | --- |
| T | [Exception](../../exception/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to get [TypeInfo](../../typeinfo/) for. |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the final class of object passed.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T) method


Implements typeof() translation. Overload for primitive types.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


| Parameter | Description |
| --- | --- |
| T | Primitive type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T | IGNORED |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the type of object passed.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectType::GetType(const T) method


Implements typeof() translation. Overload for [Nullable](../../nullable/) types.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


| Parameter | Description |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T | IGNORED |

### ReturnValue

Const reference to [TypeInfo](../../typeinfo/) structure describing the type of object passed.

## See Also

* Class [ObjectType](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
