---
title: "System::ObjectExt::CoalesceInternal metod"
linktitle: "CoalesceInternal"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::CoalesceInternal metod. Implementering av ''??''-operatorns översättning för icke-nullbara typer. Överlagring för fallet om RT2 kan konverteras till RT1 i C++."
type: docs
weight: 700
url: /sv/cpp/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal method


Implementering av översättning av '??'-operatorn för icke-nullbara typer. Överlagring för fallet då RT2 kan konverteras till RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


| Parameter | Beskrivning |
| --- | --- |
| T0 | LHS‑värdetyp. |
| T1 | Typ av lambda som kapslar RHS‑uttrycket. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | RT1 | LHS‑värde. |
| func | F | RHS‑uttryck. |

### ReturnValue

Om LHS‑värdet inte är null returneras LHS, annars beräknas RHS‑uttrycket och resultatet returneras.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
