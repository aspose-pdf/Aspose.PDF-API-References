---
title: System::AsCast method
linktitle: AsCast
second_title: Aspose.PDF for C++ API Reference
description: 'System::AsCast method. Casts the source type to the result type using ''as'' operator cast. Used when simple constructor-like cast is needed in C++.'
type: docs
weight: 13500
url: /cpp/system/ascast/
---
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used when simple constructor-like cast is needed.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used when the source and the result types are the same.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used for exception wrappers.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result. Returns nullptr if no conversion available.

## See Also

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used for casting object to exception.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result. Returns nullptr if no conversion available.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used when the source and result both are smart pointers.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result. Returns nullptr if no conversion available.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used when the source and result both are smart pointers (with expicit [SmartPtr<...>](../smartptr/) in result type).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result. Returns nullptr if no conversion available.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used for unboxing object to nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result. Returns empty nullable if no conversion available.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Invalid unboxing to non-object type.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

Always returns null.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Invalid unboxing to non-object type.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

Always returns null.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used for boxing nullable object.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used for boxing common object.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used for boxing common object.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used for string unboxing.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used for nullptr casing.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
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
## System::AsCast(const Source\&) method


Casts the source type to the result type using 'as' operator cast. Used to cast between arrays.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) to cast. |

### ReturnValue

The cast result. Returns nullptr if no conversion for any array member is available.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
