---
title: "System::DynamicCast_noexcept method"
linktitle: "DynamicCast_noexcept"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DynamicCast_noexcept method. Gamla föråldrade kast. Kommer att tas bort i framtida versioner i C++."
type: docs
weight: 18100
url: /sv/cpp/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) method


Gamla föråldrade kast. Kommer att tas bort i framtida versioner.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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
## Anmärkningar


Utför dynamisk kastning på [Exception](../exception/)-objekt. ## Deprecated
Lämnad för bakåtkompatibilitet. Använd AsCast istället.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) method


Utför dynamisk kastning på [SmartPtr](../smartptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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
## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) method


Utför dynamisk kastning på objekt till [Exception](../exception/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
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
