---
title: "Aspose::Pdf::SignaturesCompromiseDetector klass"
linktitle: "SignaturesCompromiseDetector"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::SignaturesCompromiseDetector klass. Representerar en klass för att kontrollera komprometterade signaturer i dokumentet i C++."
type: docs
weight: 17300
url: /sv/cpp/aspose.pdf/signaturescompromisedetector/
---
## SignaturesCompromiseDetector class


Representerar en klass för att kontrollera komprometterande signaturer i dokumentet.

```cpp
class SignaturesCompromiseDetector : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Check](./check/)(System::SharedPtr\<Signatures::CompromiseCheckResult\>\&) | Kontrollera dokumentets digitala signaturer för kompromettering. |
| [SignaturesCompromiseDetector](./signaturescompromisedetector/)(const System::SharedPtr\<Document\>\&) | Skapar en instans av [SignaturesCompromiseDetector](./) klass. |
## Anmärkningar


Detektorn kontrollerar endast kända sätt att kompromettera signaturer. Verifiering kan inte ge en 100% garanti för att signaturer inte är komprometterade och kan ge ett falskt negativt resultat för nya, okända komprometteringsmetoder som skiljer sig från de som testas.
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
