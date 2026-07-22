---
title: "Aspose::Pdf::SignaturesCompromiseDetector::Check metod"
linktitle: "Check"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::SignaturesCompromiseDetector::Check metod. Kontrollerar dokumentets digitala signaturer för kompromiss i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector::Check method


Kontrollera dokumentets digitala signaturer för kompromettering.

```cpp
bool Aspose::Pdf::SignaturesCompromiseDetector::Check(System::SharedPtr<Signatures::CompromiseCheckResult> &compromiseCheckResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| compromiseCheckResult | System::SharedPtr\<Signatures::CompromiseCheckResult\>\& | Resultatet av verifieringen av dokumentet. |

### ReturnValue

Sant, om kompromissen av signaturerna inte upptäcks.
## Anmärkningar



Användning av den här metoden för ett dokument som saknar digitala signaturer kommer att returnera **Sant**.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* Class [SignaturesCompromiseDetector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
