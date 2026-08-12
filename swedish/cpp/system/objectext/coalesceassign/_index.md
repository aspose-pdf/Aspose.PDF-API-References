---
title: "System::ObjectExt::CoalesceAssign metod"
linktitle: "CoalesceAssign"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::CoalesceAssign metod. Implementation av ''??=''‑operatorns översättning i C++."
type: docs
weight: 600
url: /sv/cpp/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign method


Implementering av översättning av '??='-operatorn.

```cpp
template<typename T0,typename T1> static T0 & System::ObjectExt::CoalesceAssign(T0 &value, T1 func)
```


| Parameter | Beskrivning |
| --- | --- |
| T0 | LHS‑värdetyp. |
| T1 | Typ av lambda som kapslar RHS‑uttrycket. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | T0\& | LHS‑värde. |
| func | T1 | RHS‑uttryck. |

### ReturnValue

Om LHS‑värdet inte är null returneras LHS, annars beräknas RHS‑uttrycket och resultatet returneras.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
