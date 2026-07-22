---
title: "Aspose::Pdf::Page::IsBlank metod"
linktitle: "IsBlank"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Page::IsBlank metod. Hämtar flaggan som indikerar om sidan är tom eller inte i C++."
type: docs
weight: 4800
url: /sv/cpp/aspose.pdf/page/isblank/
---
## Page::IsBlank method


Hämtar flaggan som anger om sidan är tom eller inte.

```cpp
bool Aspose::Pdf::Page::IsBlank(double fillThresholdFactor)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillThresholdFactor | double | Fyllnadströskelvärdet som styr känsligheten för detektering. Bör ligga i intervallet [0..1). |

### ReturnValue

Sant – om sidan är tom; annars falskt.
## Anmärkningar



För att avgöra om en sida är tom eller inte beräknas förhållandet mellan det fyllda utrymmet och sidans totala utrymme. Detta förhållande jämförs med parametern fillThresholdFactor och om det är mindre anses sidan vara tom.
## Se även

* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
