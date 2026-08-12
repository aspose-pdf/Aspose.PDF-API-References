---
title: "System::Security::Cryptography::DSA klass"
linktitle: "DSA"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::DSA klass. Bas-klass för implementationer av DSA-algoritmen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.security.cryptography/dsa/
---
## DSA class


Bas-klass för implementationer av [DSA](./)-algoritmen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class DSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Create](./create/)() | Skapar standard [DSA](./)-algoritmimplementation. |
| static [Create](./create/)(const String\&) | Skapar standard [DSA](./)-algoritmimplementation. |
| static [Create](./create/)(int32_t) | Skapar standard [DSA](./)-algoritmimplementation med angiven nyckelstorlek. |
| static [Create](./create/)(const DSAParameters\&) | Skapar standard [DSA](./)-algoritmimplementation med angivna parametrar. |
| static [CreateFromXmlString](./createfromxmlstring/)(const String\&) | Skapar standard [DSA](./)-algoritmimplementation med angivna XML-kodade parametrar. |
| virtual [CreateSignature](./createsignature/)(ByteArrayPtr) | RTTI-information. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exporterar alla parametrar. |
| [FromXmlString](./fromxmlstring/)(String) override | Initierar objekt med XML‑kodade parametrar. |
| virtual [ImportParameters](./importparameters/)(DSAParameters) | Importerar alla parametrar från datastrukturen. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Beräknar hashvärdet för den angivna dataarrayen med den angivna hash‑algoritmen och signerar resultatet. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Beräknar hashvärdet för den angivna dataarrayen med den angivna hash‑algoritmen och signerar resultatet. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Beräknar hashvärdet för den angivna binära strömmen med den angivna hash‑algoritmen och signerar resultatet. |
| [ToXmlString](./toxmlstring/)(bool) override | Exporterar alla parametrar i XML‑format. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna binära strömmen är giltig. |
| virtual [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) | Verifiera [DSA](./)-signatur för den angivna datan. |
## Se även

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
