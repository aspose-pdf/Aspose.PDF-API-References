---
title: "System::StringComparer::Create‑metod"
linktitle: "Skapa"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::StringComparer::Create‑metod. Skapar kulturspecifik jämförare i C++."
type: docs
weight: 100
url: /sv/cpp/system/stringcomparer/create/
---
## StringComparer::Create method


Skapar kulturspecifik jämförare.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kultur | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Kultur att skapa jämförare för. |
| ignoreCase | bool | Om jämförare ska ignorera skiftläge. |

### ReturnValue

Pekare till nyskapat jämförare‑objekt.

## Se även

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [StringComparer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
