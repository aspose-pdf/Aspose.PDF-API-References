---
title: System::StaticCast method
linktitle: StaticCast
second_title: Aspose.PDF for C++ API Reference
description: 'System::StaticCast method. Performs static cast on non-pointer objects in C++.'
type: docs
weight: 42600
url: /cpp/system/staticcast/
---
## System::StaticCast(const TFrom\&) method


Performs static cast on non-pointer objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source object. |

### ReturnValue

Cast result if cast is allowed.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(const TFrom\&) method


Performs static cast on [Exception](../exception/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target [Exception](../exception/) type. |
| TFrom | Source [Exception](../exception/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(const TFrom *) method


Specialization for arithmetic types.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\> const\&) method


Performs static cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\>) method


Performs static cast on Objects to [Exception](../exception/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


| Parameter | Description |
| --- | --- |
| TTo | Target [Exception](../exception/) type. |
| TFrom | [Object](../object/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Source pointer. |

### ReturnValue

Cast result if cast is allowed.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(std::nullptr_t) method


Performs static cast of null objects.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |

### ReturnValue

nullptr.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(TFrom) method


Specialization for arithmetic types.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(TTo) method


Process cast from [String](../string/) to [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(WeakPtr\<TFrom\> const\&) method


Performs static cast on [WeakPtr](../weakptr/) objects.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
