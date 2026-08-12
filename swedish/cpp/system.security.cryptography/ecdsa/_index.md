---
title: "System::Security::Cryptography::ECDsa class"
linktitle: "ECDsa"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::ECDsa-klass. Bas-klass för implementationer av ECDsa‑algoritmen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1300
url: /sv/cpp/system.security.cryptography/ecdsa/
---
## ECDsa class


Bas-klass för implementationer av [ECDsa](./)‑algoritmen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ECDsa : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Create](./create/)() | Skapar standardimplementation av ECDSA‑algoritmen. |
| static [Create](./create/)(const ECCurve\&) | Skapar standardimplementation av ECDSA‑algoritmen med nyckel som just skapats över den angivna kurvan. |
| static [Create](./create/)(const ECParameters\&) | Skapar standardimplementation av ECDSA‑algoritmen med de angivna parametrarna. |
| static [Create](./create/)(const String\&) | Skapar den angivna ECDSA‑algoritmimplementeringen. |
| virtual [ExportExplicitParameters](./exportexplicitparameters/)(bool) | Exporterar explicita parametrar. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exporterar namngivna eller explicita parametrar. |
| virtual [GenerateKey](./generatekey/)(const ECCurve\&) | Genererar ett nytt offentligt/privat nyckelpar för den angivna kurvan. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | RTTI-information. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Hämtar signaturalgoritm att använda. |
| virtual [ImportParameters](./importparameters/)(const ECParameters\&) | Importerar alla parametrar från datastrukturen. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | Beräknar hashvärdet för den angivna dataarrayen med den angivna hash‑algoritmen och signerar resultatet. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | Beräknar hashvärdet för den angivna dataarrayen med den angivna hash‑algoritmen och signerar resultatet. |
| virtual [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | Beräknar hashvärdet för den angivna binära strömmen med den angivna hash‑algoritmen och signerar resultatet. |
| virtual [SignHash](./signhash/)(const ByteArrayPtr\&) | Beräknar signaturen för det angivna inmatningsvärdet. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna binära strömmen är giltig. |
| virtual [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr) | Kontrollerar datasignatur. |
## Se även

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
