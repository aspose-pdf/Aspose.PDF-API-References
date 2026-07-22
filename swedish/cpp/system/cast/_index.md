---
title: "System::Cast metod"
linktitle: "Cast"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Cast metod. Utför en typkonvertering på SmartPtr‑objekt i C++."
type: docs
weight: 15800
url: /sv/cpp/system/cast/
---
## System::Cast method


Utför en typkonvertering på [SmartPtr](../smartptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
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

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
