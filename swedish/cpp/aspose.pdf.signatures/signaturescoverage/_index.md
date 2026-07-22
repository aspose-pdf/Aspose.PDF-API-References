---
title: "Aspose::Pdf::Signatures::SignaturesCoverage-enum"
linktitle: "SignaturesCoverage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Signatures::SignaturesCoverage-enum. Representerar en enum för nivån av täckning som tillhandahålls av digitala signaturer i ett dokument i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enum


Representerar en enum för nivån av täckning som tillhandahålls av digitala signaturer i ett dokument.

```cpp
enum class SignaturesCoverage
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Odefinierad | 0 | Indikerar att statusen för digitala signaturers täckning i dokumentet är odefinierad. Detta värde används vanligtvis när en eller flera signaturer i dokumentet är komprometterade eller inte kan verifieras, vilket förhindrar en definitiv bedömning av dokumentets signaturtäckning. |
| EntirelySigned | 1 | Indikerar att dokumentet är helt täckt av digitala signaturer. Detta värde betyder att alla nödvändiga delar av dokumentet har signerats och inga signaturer är komprometterade. |
| PartiallySigned | 2 | Indikerar att dokumentet är delvis signerat, vilket betyder att en del, men inte hela, av dess innehåll är täckt av digitala signaturer. Detta värde används när vissa delar av dokumentet förblir osignerade eller exkluderas från signaturtäckningen. |

## Se även

* Namespace [Aspose::Pdf::Signatures](../)
* Library [Aspose.PDF for C++](../../)
