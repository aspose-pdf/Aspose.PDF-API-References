---
title: "Aspose::Pdf::Comparison::ComparisonMode enum"
linktitle: "ComparisonMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Comparison::ComparisonMode enum. Jämförelseläges‑enumerationen i C++."
type: docs
weight: 2100
url: /sv/cpp/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enum


Enumeration för jämförelseläge.

```cpp
enum class ComparisonMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Normal | 0 | Normalt läge. Endast mellanslag inom textfragment beaktas (beroende på hur dokumentet genereras). |
| IgnoreSpaces | 1 | Alla mellanslag ignoreras. Ändringar söks endast i ord. |
| ParseSpaces | 2 | Läget liknar normalt, men försöker ta hänsyn till visuellt avstånd mellan textfragment baserat på avstånd. Att känna igen antalet mellanslag mellan fragment kan vara inexakt eftersom det starkt beror på hur dokumenten genereras. Om dokument skapas av olika generatorer kan det finnas felaktigheter vid jämförelse av mellanslag mellan textfragment. |

## Se även

* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
