---
title: "System::InitObject metod"
linktitle: "InitObject"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::InitObject metod. Startar initiering av ett objekt med delat ägande i C++."
type: docs
weight: 22500
url: /sv/cpp/system/initobject/
---
## System::InitObject method


Startar initiering av ett objekt med delat ägande.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att initiera |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | const SharedPtr\<T\>\& | [Object](../object/) att initiera |

### ReturnValue

ObjectBuilder konfigurerad för konstruktion av delade pekare
## Anmärkningar



[Object](../object/) initialization must be finished with [Get()](../get/) call 

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
