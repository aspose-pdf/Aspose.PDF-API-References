---
title: "System::Array::Exists-metod"
linktitle: "Exists"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::Exists-metod. Avgör om det angivna Array-objektet innehåller ett element som uppfyller kraven i det angivna predikatet i C++."
type: docs
weight: 5200
url: /sv/cpp/system/array/exists/
---
## Array::Exists method


Avgör om det angivna [Array](../)-objektet innehåller ett element som uppfyller kraven i det angivna predikatet.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | ArrayPtr\<T\> | Arrayen att söka efter elementet i |
| matcha | std::function\<bool(T)> | Funktionsobjekt som definierar krav och kontrollerar om ett element uppfyller dem |

### ReturnValue

Sant om **arr** innehåller ett element som uppfyller krav definierade av **match**

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
