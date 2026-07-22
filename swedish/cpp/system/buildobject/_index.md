---
title: "System::BuildObject-metoden"
linktitle: "BuildObject"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::BuildObject-metoden. Bygg ett objekt med delat ägande i C++."
type: docs
weight: 15700
url: /sv/cpp/system/buildobject/
---
## System::BuildObject method


Bygg ett objekt med delat ägande.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att skapa |
| Argument | Argumenttyper för objektkonstruktion |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Argument att vidarebefordra till objektkonstruktorn |

### ReturnValue

ObjectBuilder konfigurerad för konstruktion av delade pekare
## Anmärkningar



Skapar en [SharedPtr<T>](../sharedptr/) och returnerar en byggare för den
[Object](../object/) construction must be finished with [Get()](../get/) call 

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
