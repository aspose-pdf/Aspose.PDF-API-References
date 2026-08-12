---
title: "System::ConstCast‑metod"
linktitle: "ConstCast"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ConstCast‑metod. Slut på föråldrade kast i C++."
type: docs
weight: 16600
url: /sv/cpp/system/constcast/
---
## System::ConstCast method


Slut på föråldrade kast.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |
| TFrom | Källpointee-typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<TFrom\>\& | Källpekare. |

### ReturnValue

Kastresultat om kast är tillåtet eller nullptr annars.
## Anmärkningar


Utför const‑kast på [SmartPtr](../smartptr/)‑objekt.
## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
