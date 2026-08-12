---
title: "System::BuildArray metod"
linktitle: "BuildArray"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::BuildArray metod. Bygg en array i C++."
type: docs
weight: 15600
url: /sv/cpp/system/buildarray/
---
## System::BuildArray method


Bygg en array.

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp för den array som ska byggas |

### ReturnValue

ObjectBuilder konfigurerad för array‑konstruktion
## Anmärkningar



Skapar en [ArrayPtr<T>](../arrayptr/) och returnerar en byggare för den
[Object](../object/) construction must be finished with [Get()](../get/) call 

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
