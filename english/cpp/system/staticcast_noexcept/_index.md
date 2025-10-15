---
title: System::StaticCast_noexcept method
linktitle: StaticCast_noexcept
second_title: Aspose.PDF for C++ API Reference
description: 'System::StaticCast_noexcept method. Performs static cast on Exception objects in C++.'
type: docs
weight: 42100
url: /cpp/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(const TFrom\&) method


Performs static cast on [Exception](../exception/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target [Exception](../exception/) type. |
| TFrom | Source [Exception](../exception/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed or nullptr otherwise.

## Deprecated
Left for backwards compatibility. Use AsCast instead. 

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) method


Performs static cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed or nullptr otherwise.

## Deprecated
Left for backwards compatibility. Use AsCast instead. 

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\>) method


Performs static cast on Objects to [Exception](../exception/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


| Parameter | Description |
| --- | --- |
| TTo | Target [Exception](../exception/) type. |
| TFrom | [Object](../object/) type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Source pointer. |

### ReturnValue

Cast result if cast is allowed or nullptr otherwise.

## Deprecated
Left for backwards compatibility. Use AsCast instead. 

## See Also

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) method


Performs static cast on [WeakPtr](../weakptr/) objects.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Source pointer. |

### ReturnValue

Cast result if cast is allowed or nullptr otherwise.

## Deprecated
Left for backwards compatibility. Use AsCast instead. 

## See Also

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
