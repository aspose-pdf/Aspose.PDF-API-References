---
title: "System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode metod"
linktitle: "GetHashCode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode metod. Hämtar hash‑kod för en godtycklig typ. Anropar Object::GetHashCode() för att göra det i C++."
type: docs
weight: 100
url: /sv/cpp/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode method


Hämtar hash‑kod för en godtycklig typ. Anropar [Object::GetHashCode()](../../../system/object/gethashcode/) för att göra det.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ att hämta hash‑kod för. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | SmartPtr\<T\> const\& | [Object](../../../system/object/) för att hämta information från. |

### ReturnValue

Hash‑kodvärde som beräknas av målimplementeringen.

## Se även

* Class [SmartPtr](../../../system/smartptr/)
* Class [RuntimeHelpers](../)
* Namespace [System::Runtime::CompilerServices](../../)
* Library [Aspose.PDF for C++](../../../)
