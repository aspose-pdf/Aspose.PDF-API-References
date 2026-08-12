---
title: "System::DynamicCast-metod"
linktitle: "DynamicCast"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DynamicCast-metoden. Utför dynamisk kastning på Exception‑objekt i C++."
type: docs
weight: 17400
url: /sv/cpp/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) method


Utför dynamisk kastning på [Exception](../exception/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målt [Exception](../exception/) typ. |
| TFrom | Käll [Exception](../exception/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const TFrom\& | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(SmartPtr\<TFrom\> const\&) method


Utför dynamisk kastning på [SmartPtr](../smartptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |
| TFrom | Källpointee-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(SmartPtr\<TFrom\>) method


Packar upp en inkapslad enum via kast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målenumertyp. |
| TFrom | Källpointee-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Pekare till objektet att packa upp data från. |

### ReturnValue

Uppackad enum‑värde.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(SmartPtr\<TFrom\>) method


Utför dynamisk kastning på objekt till [Exception](../exception/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målt [Exception](../exception/) typ. |
| TFrom | [Object](../object/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(std::nullptr_t) method


Utför dynamisk kastning av null‑objekt.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |

### ReturnValue

nullptr.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(TFrom\&) method


Utför dynamisk kastning på icke‑pekarobjekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målt typ. |
| TFrom | Källtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | TFrom\& | Källobjekt. |

### ReturnValue

Kastresultat.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DynamicCast(TFrom) method


Utför dynamisk kastning från IntPtr till pekare.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målt typ. |
| TFrom | Källtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | TFrom | Käll‑IntPtr‑värde. |

### ReturnValue

Kastresultat.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
