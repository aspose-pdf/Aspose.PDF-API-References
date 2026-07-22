---
title: "System::Array::FindAll method"
linktitle: "FindAll"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::FindAll method. Hämtar alla element som matchar villkoren som definieras av det angivna predikatet i C++."
type: docs
weight: 5400
url: /sv/cpp/system/array/findall/
---
## Array::FindAll method


Hämtar alla element som matchar villkoren som definierats av det angivna predikatet.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) för att söka element i |
| matcha | System::Predicate\<T\> | Ett predikat som definierar villkoren för att matcha array‑element mot |

### ReturnValue

En [Array](../) som innehåller alla element som matchar villkoren definierade av det angivna predikatet, om sådana finns; annars en tom [Array](../).

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
