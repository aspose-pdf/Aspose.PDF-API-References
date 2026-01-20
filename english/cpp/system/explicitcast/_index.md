---
title: System::ExplicitCast method
linktitle: ExplicitCast
second_title: Aspose.PDF for C++ API Reference
description: 'System::ExplicitCast method. Casts the source type to the result type using explicit cast. Used when the source and the result types are the same in C++.'
type: docs
weight: 18500
url: /cpp/system/explicitcast/
---
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used when the source and the result types are the same.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Enum [Base64FormattingOptions](../base64formattingoptions/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used when simple constructor-like cast is needed.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for exception wrappers.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for casting object to exception.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used when the source and result both are smart pointers (without expicit [SmartPtr<...>](../smartptr/) in result type).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used when the source and result both are smart pointers (with expicit [SmartPtr<...>](../smartptr/) in result type).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for unboxing object to nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used to box nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for unboxing nullable object.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for enum boxing.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for copying value types to heap when value type should be referenced as smart pointer (in generics constrained with interface type but specialized with structure implementing this interface).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for getting interfaces from value types.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for common boxing.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for [System::String](../string/) boxing.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for unboxing interfaces.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for common unboxing.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for nullptr casting.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Casts the source type to the result type using explicit cast. Used for casting between arrays.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(Source) method


Casts the source type to the result type using explicit cast. Used when the casting raw pointer to smart pointer.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | Source | [Object](../object/) to cast. |

### ReturnValue

The cast result.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
