---
title: "System::ObjectExt::Coalesce metod"
linktitle: "Kombinera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::Coalesce metod. Implementering av ''??''-operatorns översättning för nullable-typer i C++."
type: docs
weight: 500
url: /sv/cpp/system/objectext/coalesce/
---
## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) method


Implementering av översättning av '??'-operatorn för nullbara typer.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


| Parameter | Beskrivning |
| --- | --- |
| T0 | LHS‑värdetyp. |
| T1 | Typ av lambda som kapslar RHS‑uttrycket. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | System::Nullable\<T0\> | LHS‑värde. |
| func | T1 | RHS‑uttryck. |

### ReturnValue

Om LHS‑värdet inte är null returneras LHS, annars beräknas RHS‑uttrycket och resultatet returneras.

## Se även

* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Coalesce(T0, T1) method


Implementering av översättning av '??'-operatorn för icke‑nullbara typer.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


| Parameter | Beskrivning |
| --- | --- |
| T0 | LHS‑värdetyp. |
| T1 | Typ av lambda som kapslar RHS‑uttrycket. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | T0 | LHS‑värde. |
| func | T1 | RHS‑uttryck. |

### ReturnValue

Om LHS‑värdet inte är null returneras LHS, annars beräknas RHS‑uttrycket och resultatet returneras.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
