---
title: System::DynamicCast method
linktitle: DynamicCast
second_title: Aspose.PDF for C++ API Reference
description: 'System::DynamicCast method. Performs dynamic cast on Exception objects in C++.'
type: docs
weight: 16800
url: /cpp/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) method


Performs dynamic cast on [Exception](../exception/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
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
## System::DynamicCast(SmartPtr\<TFrom\> const\&) method


Performs dynamic cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
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
## System::DynamicCast(SmartPtr\<TFrom\>) method


Unboxes boxed enum via cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target enum type. |
| TFrom | Source pointee type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Pointer to the object to unbox data from. |

### ReturnValue

Unboxed enum value.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(SmartPtr\<TFrom\>) method


Performs dynamic cast on Objects to [Exception](../exception/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
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
## System::DynamicCast(std::nullptr_t) method


Performs dynamic cast of null objects.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
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
## System::DynamicCast(TFrom\&) method


Performs dynamic cast on non-pointer objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

| Parameter | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | Source object. |

### ReturnValue

Cast result.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(TFrom) method


Performs dynamic cast from IntPtr to pointer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | Source IntPtr value. |

### ReturnValue

Cast result.

## Deprecated
Left for backwards compatibility. Use ExplicitCast instead. 

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
