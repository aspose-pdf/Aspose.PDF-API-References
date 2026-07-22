---
title: "System::MakeYieldEnumerable metod"
linktitle: "MakeYieldEnumerable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::MakeYieldEnumerable metod. Skapar ett IEnumerable från en yield-funktion i C++."
type: docs
weight: 26100
url: /sv/cpp/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable method


Skapar ett IEnumerable från en yield-funktion.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i sekvensen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Yield-funktionen som ska köras |

### ReturnValue

Delad pekare till IEnumerable

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
