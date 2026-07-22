---
title: "System::Array::Find metod"
linktitle: "Find"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::Find metod. Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet i C++."
type: docs
weight: 5300
url: /sv/cpp/system/array/find/
---
## Array::Find method


Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | System::ArrayPtr\<T\> | [Array](../) för att söka ett element i |
| matcha | System::Predicate\<T\> | Ett predikat som definierar villkoren för att matcha array‑element mot |

### ReturnValue

Kopia av det första elementet i arrayen som uppfyller villkoren definierade av predikatet, annars standardvärdet av typen T

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
