---
title: "System::StaticCast-metod"
linktitle: "StaticCast"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::StaticCast-metod. Utför en statisk kastning på icke‑pekarobjekt i C++."
type: docs
weight: 43300
url: /sv/cpp/system/staticcast/
---
## System::StaticCast(const TFrom\&) method


Utför en statisk kastning på icke‑pekarobjekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målt typ. |
| TFrom | Källtyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const TFrom\& | Källobjekt. |

### ReturnValue

Kastresultat om kast är tillåtet.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(const TFrom\&) method


Utför statisk cast på [Exception](../exception/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
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
## System::StaticCast(const TFrom *) method


Specialisering för aritmetiska typer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(SmartPtr\<TFrom\> const\&) method


Utför statisk kast på [SmartPtr](../smartptr/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
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
## System::StaticCast(SmartPtr\<TFrom\>) method


Utför statisk kast på objekt till [Exception](../exception/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
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
## System::StaticCast(std::nullptr_t) method


Utför statiskt kast av null-objekt.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
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
## System::StaticCast(TFrom) method


Specialisering för aritmetiska typer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(TTo) method


Bearbeta kast från [String](../string/) till [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## Se även

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCast(WeakPtr\<TFrom\> const\&) method


Utför statisk kast på [WeakPtr](../weakptr/) objekt.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |
| TFrom | Källpointee-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | WeakPtr\<TFrom\> const\& | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet.

## Deprecated
Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
