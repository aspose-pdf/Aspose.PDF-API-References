---
title: "System::SafeInvoke method"
linktitle: "SafeInvoke"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::SafeInvoke method. Implementering av ''?.''‑operatorns översättning i C++."
type: docs
weight: 37700
url: /sv/cpp/system/safeinvoke/
---
## System::SafeInvoke method


Implementering av ''?.''‑operatorns översättning.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


| Parameter | Beskrivning |
| --- | --- |
| T0 | uttryckstyp. |
| T1 | Typ av lambda som kapslar in ''WhenTrue''‑uttrycket. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | T0\&& | uttrycks värde. |
| func | T1\&& | ''WhenTrue''‑uttrycket bundet till funktor. |

### ReturnValue

Om expr‑värdet inte är null, returneras func anropad med dess värde som första argument, annars returneras null.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
