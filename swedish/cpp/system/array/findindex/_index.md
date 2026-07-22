---
title: "System::Array::FindIndex-metod"
linktitle: "FindIndex"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::FindIndex-metod. Söker efter det första elementet i den angivna arrayen som uppfyller villkoren i det angivna predikatet i C++."
type: docs
weight: 5500
url: /sv/cpp/system/array/findindex/
---
## Array::FindIndex method


Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) för att söka ett element i |
| matcha | System::Predicate\<T\> | Ett predikat som definierar villkoren för att matcha array‑element mot |

### ReturnValue

Index för det första elementet i arrayen som uppfyller villkoren som definieras av predikatet, annars -1

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
