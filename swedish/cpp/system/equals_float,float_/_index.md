---
title: "System::Equals< float, float > metod"
linktitle: "Equals< float, float >"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Equals< float, float > metod. Specialisering för enkelprecisions flyttal. Även om två flyttals‑NaN‑värden definieras av IEC 60559:1989 att alltid jämföras som olika, kräver kontraktet för System.Object.Equals att överskuggningar måste uppfylla kraven för en ekvivalensoperator. Därför returnerar System.Double.Equals och System.Single.Equals True när två NaN jämförs, medan likhetsoperatorn returnerar False i det fallet, enligt standarden i C++."
type: docs
weight: 18900
url: /sv/cpp/system/equals_float,float_/
---
## System::Equals< float, float > method


Specialisering för enkelprecisions flyttal. Även om två flyttals‑NaN‑värden definieras av IEC 60559:1989 att alltid jämföras som olika, kräver kontraktet för [System.Object.Equals](../object/equals/) att överskuggningar måste uppfylla kraven för en ekvivalensoperator. Därför returnerar System.Double.Equals och System.Single.Equals True när två NaN jämförs, medan likhetsoperatorn returnerar False i det fallet, enligt standarden.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const float\& | Den första jämförelsetermen |
| b | const float\& | Den andra jämförelsetermen |

### ReturnValue

True om båda värdena är NaN eller är lika, annars - false

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
