---
title: System::DynamicCast_noexcept method
linktitle: DynamicCast_noexcept
second_title: Aspose.PDF for C++ API Reference
description: 'System::DynamicCast_noexcept method. Old obsolete casts. Will be removed in future versions in C++.'
type: docs
weight: 17600
url: /cpp/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) method


Old obsolete casts. Will be removed in future versions.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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
## Remarks


Performs dynamic cast on [Exception](../exception/) objects. ## Deprecated
Left for backwards compatibility. Use AsCast instead. 

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) method


Performs dynamic cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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
## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) method


Performs dynamic cast on Objects to [Exception](../exception/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
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
