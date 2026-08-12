---
title: "System::StaticCast_noexcept metod"
linktitle: "StaticCast_noexcept"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::StaticCast_noexcept metod. Utför statisk cast på Exception-objekt i C++."
type: docs
weight: 44200
url: /sv/cpp/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(const TFrom\&) method


Utför statisk cast på [Exception](../exception/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målt [Exception](../exception/) typ. |
| TFrom | Käll [Exception](../exception/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const TFrom\& | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet eller nullptr annars.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd AsCast istället.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) method


Utför statisk kast på [SmartPtr](../smartptr/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |
| TFrom | Källpointee-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet eller nullptr annars.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd AsCast istället.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(SmartPtr\<TFrom\>) method


Utför statisk kast på objekt till [Exception](../exception/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målt [Exception](../exception/) typ. |
| TFrom | [Object](../object/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet eller nullptr annars.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd AsCast istället.

## Se även

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) method


Utför statisk kast på [WeakPtr](../weakptr/) objekt.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |
| TFrom | Källpointee-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet eller nullptr annars.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd AsCast istället.

## Se även

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
