---
title: "System::Cast_noexcept‑metod"
linktitle: "Cast_noexcept"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Cast_noexcept‑metod. Utför en typkonvertering på SmartPtr‑objekt i C++."
type: docs
weight: 15900
url: /sv/cpp/system/cast_noexcept/
---
## System::Cast_noexcept method


Utför en typkonvertering på [SmartPtr](../smartptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
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

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
