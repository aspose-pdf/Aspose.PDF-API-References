---
title: "System::ForceStaticCast metod"
linktitle: "ForceStaticCast"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ForceStaticCast metod. Utför en riktig statisk kastning på SmartPtr‑objekt i C++."
type: docs
weight: 20900
url: /sv/cpp/system/forcestaticcast/
---
## System::ForceStaticCast method


Utför en riktig statisk kastning på [SmartPtr](../smartptr/)‑objekt.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |
| TFrom | Källpointee-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | SmartPtr\<TFrom\> const\& | Källpekare. |

### ReturnValue

Kasta resultatet om kastet är tillåtet, annars är beteendet odefinierat.

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
