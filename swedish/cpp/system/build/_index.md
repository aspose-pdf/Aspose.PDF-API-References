---
title: "System::Build-metod"
linktitle: "Build"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Build-metod. Skapa ett objekt med direkt ägarskap i C++."
type: docs
weight: 15500
url: /sv/cpp/system/build/
---
## System::Build method


Skapa ett objekt med direkt ägarskap.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att skapa |
| Argument | Argumenttyper för objektkonstruktion |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Argument att vidarebefordra till objektkonstruktorn |

### ReturnValue

ObjectBuilder konfigurerad för direkt objektkonstruktion
## Anmärkningar



[Object](../object/) construction must be finished with [Get()](../get/) call 

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
